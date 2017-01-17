# html-imports-benchmark

Performance tests for html-imports v0 vs v1 implementations.

```bash
$ npm install -g polymer-cli
$ bower install
$ polymer serve
```

Then open `index.html` and run the tests.

## Results

Averages of 10 runs on different browsers.

Browser   | v0      | v1      | v1 (es6) | v0-v1 (ms) | v0-v1 (%) | v1-v1 (es6) (ms) | v1-v1 (es6) (%)
--------- | ------- | ------- | -------- | ---------- | --------- | ---------------- | ---------------
Chrome    | 484.99  | 478.36  | 468.73   | 6.64       | 1.37      | 9.63             | 2.01
Canary    | 304.44  | 279.86  | 264.23   | 24.59      | 8.08      | 15.63            | 5.58
Firefox   | 2974.46 | 1231.76 | 1201.02  | 1742.7     | 58.59     | 30.74            | 2.5
Safari 10 | 459.76  | 473.33  | 458.85   | -13.57     | -2.95     | 14.48            | 3.06
Safari TP | 330.74  | 326.61  | 323.37   | 4.13       | 1.25      | 3.24             | 0.99
MS Edge   | 4707.59 | 3741.18 | 3969.83  | 966.4      | 20.53     | -228.64          | -6.11
MS IE11   | 5821.1  | 4983.08 | -        | 838.01     | 14.4      | -                | -
