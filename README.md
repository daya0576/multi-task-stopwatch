> Simple stop watch, allowing for timing of a number of tasks, exposing total running time and running time for each
> named task. - inspired by Spring Framework

## Usage

```python


sw = StopWatch("title")

sw.start("eat")
time.sleep(0.12)
sw.stop()

sw.start("sleep")
time.sleep(0.60)
sw.stop()

sw.start("work")
time.sleep(0.25)
sw.stop()

print(sw.pretty_print())


```

## Install

### Pip

Install via pip:

```shell
pip install -i simple-stopwatch
```