## Model Design

### Modules

Modules may be included in a class to add the behaviors of the defined in the module to the class. A class may include multiple modules.

#### References

* [Tutorial: Classes, Inheritance, Modules and Mixins in Ruby on Rails](https://www.webascender.com/blog/tutorial-classes-inheritance-modules-mixins-ruby-rails/) (2016)
* [Where to put Rails modules](https://www.codewithjason.com/put-rails-modules/) (2018) - TL;DR modules in `lib`, add `    config.eager_load_paths += %W(#{config.root}/lib)` to `config/application.rb` to handle loading your modules (mixins).
* [Ruby does not support Multiple Inheritance. Ruby uses Mixin instead](http://techenthu.in/2017/09/14/ruby-not-support-multiple-inheritance-ruby-uses-mixin-instead/) (2017)

### Single-table Inheritance (STI), Multi-table Inheritance (MTI), and Polymorphism

#### STI

Useful when subclasses (models) share data, but have different behaviors. As the data between the classes diverges the benefits of STI diminish.

All of the subclasses share a common controller (the base class controller).

```rails
class Person < ActiveRecord::Base
end
class Student < Person ; end
```

#### MTI

Useful when subclasses share behaviors, but have only a sparse data overlap.

#### Polymorphism

#### References

* [ActiveRecord::Inheritance (Single table inheritance)](https://api.rubyonrails.org/classes/ActiveRecord/Inheritance.html)
* [How (and When) to Use Single Table Inheritance in Rails](https://eewang.github.io/blog/2013/03/12/how-and-when-to-use-single-table-inheritance-in-rails/) (2013)
* [Refactoring our Rails app out of single-table inheritance](https://about.futurelearn.com/blog/refactoring-rails-sti) (2014)
* [Single Table Inheritance with Rails 4 - Part 1](https://devblast.com/b/single-table-inheritance-with-rails-4-part-1) (2014)
* [Single Table Inheritance with Rails 4 - Part 2](https://devblast.com/b/single-table-inheritance-with-rails-4-part-2) (2014)
* [Single Table Inheritance with Rails 4 - Part 3](https://devblast.com/b/single-table-inheritance-with-rails-4-part-3) (2014)
