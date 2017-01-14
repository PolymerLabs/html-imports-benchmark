# html-imports-benchmark

Performance tests for html-imports v0 vs v1 implementations.

```bash
$ npm install -g polymer-cli
$ bower install
$ polymer serve
```

Then open `index.html` and run the tests.

## Results

Averages of 20 runs on different browsers.

Browser                   | v0     | v1      | v0 - v1 (ms) | v0 - v1 (%) | v1 (es6) | es5 - es6
------------------------- | ------ | ------- | ------------ | ----------- | -------- | ---------
chrome                    | 514.8  | 509.8   | 5            | 0.97%       | 497.65   | 12.15
firefox                   | 2167   | 845.4   | 1321.6       | 60.99%      | 839.8    | 5.6
safari technology preview | 262.75 | 264.15  | -1.4         | -0.53%      | 257.1    | 7.05
safari                    | 418.45 | 361.05  | 57.4         | 13.72%      | 362.65   | -1.6
MS Edge                   | 5488.9 | 4264.05 | 1224.85      | 22.32%      | 4283.95  | -19.9
MS IE11                   | 5731   | 4103.5  | 1627.5       | 28.40%      | -        | -
