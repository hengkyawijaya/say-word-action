# say-word-action
You only need setup like this on your repo

```
name: Say Word
on:
  pull_request:
    types: [closed]

jobs:
  say_word_job:
    runs-on: ubuntu-latest
    name: Just Say Word
    steps:
    - name: Say Word
      id: say_word
      uses: hengkyawijaya/say-word-action@v0.0.1
      with:
        word: 'hello'
```

Thanks
