##Our awesome TV adapter

```
Class AwesomeTVAdapter extends AwesomeTV {
  function powerOn() { turnOn() };
  function powerOff() { turnOff() };
}
```

or

```
Class AwesomeTVAdapter {
  AwesomeTV awesomeTV;

  AwesomeTVAdaptor(awesomeTV) {
    this.awesomeTV = awesomeTV;
  }

  function powerOn() { awesomeTV.turnOn() };
  function powerOff() { awesomeTV.turnOff() };
}
```
