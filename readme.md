## Introduction
This is a simple script to fetch all daily puzzles on chess.com. 

### Job
```sh
cd job

npm install

npm start {number of month}
# for example npm start 10 will pull last 10 months from current month

```

To pull all available puzzle

```
npm start
```

The puzzle will fetch month by month and stored in the puzzle folder in JSON format.

### UI

```sh
cd app
npm run dev
```