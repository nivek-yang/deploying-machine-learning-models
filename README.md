# Deploying Machine Learning Models
For the documentation, visit the course on Udemy.

1) Checkout the course at the 10.3 commit

```
git checkout <commit_hash>
```

2) Set the heroku remote as shown in the lecture with 

```
heroku git:remote -a YOUR-HEROKU-APP-NAME
```

3) [Not shown in the video] Then create a new branch with 

```
git checkout -b my-test-branch
```

4) [Not shown in the video] Then when you push to heroku, specify your branch 

```
git push heroku my-test-branch:master
```