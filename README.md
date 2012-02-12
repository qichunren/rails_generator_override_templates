### Usage
```
cd your_rails_project
cd lib
git clone git://github.com/qichunren/rails_generator_override_templates.git
mv rails_generator_override_templates templates 
# then your scaffold_controller, controller, helper, and erb views will follow override templates.
```

### What is the difference with the Rails official templates  ?

+ I add **encoding: utf-8** into generated rb file head.
+ I change scaffold erb file with [twitter-bootstrap](http://twitter.github.com/bootstrap/) style.

### Resources

+ [Creating and Customizing Rails Generators & Templates](http://guides.rubyonrails.org/generators.html#customizing-your-workflow-by-changing-generators-templates)
+ [Rails generators source code](https://github.com/rails/rails/tree/master/railties/lib/rails/generators)
+ [Twitter bootstrap](http://twitter.github.com/bootstrap/)