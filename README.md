# BPMTimer

```
class mpBPMTimerClass: private  mpTimerClass {
  public:
    enum {
//      PPQN1,  PPQN2, PPQN4,
      PPQN8,  PPQN12, PPQN16, PPQN24,
      PPQN32, PPQN48, PPQN72, PPQN96,
    };

    setBPM(byte bpm);
    setPPQN(byte ppqn);

    getMicroseconds();
};
```
