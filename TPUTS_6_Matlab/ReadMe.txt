run on console

 [x,fs] = audioread('car.wav');
 [out,~] = WienerNoiseReduction(x,fs,100) ;
 soundsc(out(1:122000),fs);


  [x,fs] = audioread('car.wav');
 [out,~] = WienerNoiseReduction(x,fs,100000) ;
 soundsc(out(1:122000),fs);