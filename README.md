## karmelalla readme:

### Resize Instruction:

* open terminal config ```$ zshconfig```
* paste in the end ```unsetopt nomatch```
* restart terminal window
* go to the project folder and install gems
```
$ cd [project_name]
$ bundle install
```
* run rake command:
```
$ rake resize[2017-01-15-first-weekend] # 1st argument is path
$ rake resize[2017-01-15-first-weekend,100] # 1st argument is path and 2nd is image width 
```

Also you can change width in ```_config.yml``` in your project folder. By default it's: 
```
...
image_width: 300 
image_quality: 85
```

### Send email:

```
$ jekyll mail # send last post
$ jekyll mail 2017-03-17-5years # send post by name
$ jekyll mail --test # Open email for preview without sending
```
