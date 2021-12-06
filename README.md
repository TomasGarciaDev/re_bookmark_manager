## Re Bookmark Manager

## User Stories

```
As a time-pressed user
So that I can quickly go to web sites I regularly visit
I would like to see a list of bookmarks
```
```
As a time-pressed user
So that I can quickly go to web sites I regularly visit
I would like to see a list of bookmarks
```

## Domain Model
<img width="862" alt="Screenshot 2021-12-06 at 22 20 28" src="https://user-images.githubusercontent.com/86299300/144932069-7f42c34e-49eb-42ed-b5f8-269114b3104e.png">

## Model View Controller (MVC) conventions:
```
| Component   | Responsibility                                | Refactor                                |
|------------ |---------------------------------------------  |---------------------------------------- |
| Model       | Encapsulate logic with relevant data          | Encapsulate bookmark data in a class    |
| View        | Display the result to a user                  | Show the bookmark data in a list        |
| Controller  | Get data from the model and put in the view   | Render bookmark data into to the view   |
```
