## Microblog Frontend

## To start
```
npm start
```

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

## Component architecture
```
App
├── NavBar
├── BlogPostForm
├─┬ HomePage
│ └─┬ BlogCard
│   └── VoteCounter
└─┬ BlogPost
  ├── BlogPostForm
  ├── VoteCounter
  └─┬ CommentArea
    ├── Comment
    └── CommentForm
```