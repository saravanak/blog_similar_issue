# blog_similar_issue
Repo to demonstrate an issue  in middlema-blog-similar extension

To replicate, clone this repo under `~/.middleman`. 

Then initialize a new middleman project based on the above template:

```sh
middleman init --template=blog_similar_issue
bundler install --local
middleman server --verbose
```

Then access `localhost:4567` in the browser, You should see the following message on the console:
```sh
[2015-06-11 11:47:21] ERROR SystemStackError: stack level too deep
	/Users/x/.rvm/gems/ruby-2.1.5/gems/middleman-core-3.3.12/lib/middleman-core/core_extensions/front_matter.rb:212
```	



