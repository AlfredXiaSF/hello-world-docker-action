# Hello world docker action
This action prints "Hello World" or "Hello" + the name of person to greet to the log

## Inputs
**必填** 要问候的人员姓名。默认值为'“world”'。

## Outputs
### 'time'
我们问候您的时间。

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
