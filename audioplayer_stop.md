



audioplayer_stop


audioplayer_stop

Stops an audioplayer object.

## Syntax

- stop(playObj)

## Input argument

 - playObj - an audioplayer object.

## Description

<b>stop</b> stops an audioplayer object.

## Example

```Nelson
signal = rand(2, 44100) - 0.5;
playObj = audioplayer(signal, 44100, 16)
play(playObj)
sleep(2)
stop(playObj)
delete(playObj)
playObj
```

## See also

audioplayer.md audioplayer, play.md play.
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET



