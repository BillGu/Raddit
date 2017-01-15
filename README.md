# Raddit

Raddit is a simple link aggregator application scripted in ROR and deployed on heroku, where users can submit links and sort content based on tags/interests.
You just need to simply create an account and login to submit/edit/delete a link.

## Getting Started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```
Or to see it working live visit-
* [Raddit](https://radddit.herokuapp.com/)

### Todos

* Improve frontend, add bootstrap and other styling.
* Add sorting based on tags/interests.
* Add upvote/downvote mechanism.
* Add comments section using disqus. 



## Deployment

Install heroku on your system and to deploy :

```
$ heroku create
```
To rename your app:

```
$ heroku rename "new_app_name"
```
To deploy your app on the heroku server:

```
$ git push heroku master
```


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

