# Read lists

### [active-record-basics](https://www.theodinproject.com/courses/ruby-on-rails/lessons/active-record-queries#querying-basics)
##### [active_record_querying](https://guides.rubyonrails.org/active_record_querying.html)
1. Retrieving objects from the database
    - return a collection instance of relation model : where / group / ...
    - return a single instance of the model : find / first / ...
2. Conditions : Array / Hash
3. Order
4. Select
5. Limit / Offset
6. Group
7. Having
8. Overriding Conditions
9. Null Relation
10. Readonly Objects
11. Locking records for update
12. Joining tables
14. Scopes
18. Find or created by
19. Finding by SQL
21. Calculations

##### [existence-of-objects](https://guides.rubyonrails.org/active_record_querying.html#existence-of-objects)
- exists?
- any?
- many?

### [active-record-associations](https://www.theodinproject.com/courses/ruby-on-rails/lessons/active-record-associations)
##### [association_basics](https://guides.rubyonrails.org/association_basics.html)
1. Why associations? : The associations between two models make common operations simpler and easier in code.
2. Types of associations : belongs_to / has_one / has_many / has_many :through / has_one :through / has_and_belongs_to_many
3. Tips, Tricks, and Warnings
4. Details association reference

### [associations](https://www.theodinproject.com/courses/ruby-on-rails/lessons/associations)

### [active-record-callbacks](https://www.theodinproject.com/courses/ruby-on-rails/lessons/active-record-callbacks)
##### https://guides.rubyonrails.org/active_record_callbacks.html#callback-registration
1. The Object Life Cycle
Callbacks allow you to trigger logic before or after an alteration of an object's state.
2. Callbacks Overview
3. Available Callbacks
4. Running Callbacks
5. Skipping Callbacks
6. Halting Execution
7. Rational Callbacks
8. Conditional Callbacks
9. Callback Classes
10. Transaction Callbacks

##### https://samuelmullen.com/2012/01/guidelines-for-using-activerecord-callbacks/
1. Use callbacks only if they can be run every time and in every circumstance they are triggered.
2. Never create callbacks which exceed the model’s responsibility.
3. If you have to stub callbacks during testing, you are violating one of the previous rules of thumb.
+ Additional : [Deorator](https://samuelmullen.com/2011/12/sending-notifications-using-decorators-instead-of-callbacks/) ?

##### [Wiki callbacks](https://en.wikibooks.org/wiki/Ruby_on_Rails/ActiveRecord/Callbacks)


### [Advanced forms](https://www.theodinproject.com/courses/ruby-on-rails/lessons/advanced-forms)
+ Select tag / Nested forms / Deleting nested form object / Many-to-Many relationships / Simple form
##### [Form helpers](https://guides.rubyonrails.org/form_helpers.html)
3. (3) Option Tags from a Collection of Arbitrary Objects ?
5. Uploading Files ?
7. Understanding Parameter Naming Conventions ?
+ Additional : [Many-to-Many](https://thoughtbot.com/blog/accepts-nested-attributes-for-with-has-many-through) / [Simple Form](https://github.com/plataformatec/simple_form)

+ Additional :
  * https://api.rubyonrails.org/classes/ActiveRecord/NestedAttributes/ClassMethods.html
  * https://stackoverflow.com/questions/15648396/rails-how-to-manage-nested-attributes-without-using-accepts-nested-attributes?rq=1
  * https://stackoverflow.com/questions/941594/understanding-the-rails-authenticity-token
  * http://daniel.fone.net.nz/blog/2013/05/20/a-better-way-to-manage-the-rails-secret-token/

##### [Nested Form](https://www.createdbypete.com/working-with-nested-forms-and-a-many-to-many-association-in-rails-4/)

### [Conclusion](https://www.theodinproject.com/courses/ruby-on-rails/lessons/conclusion-ruby-on-rails)
##### [Rails Command Line](https://guides.rubyonrails.org/command_line.html)
##### [Caching with rails](https://guides.rubyonrails.org/caching_with_rails.html)

### API
##### [own-api](https://www.theodinproject.com/courses/ruby-on-rails/lessons/apis-and-building-your-own)
##### [external-api](https://www.theodinproject.com/courses/ruby-on-rails/lessons/working-with-external-apis)
1. [OAuth 2.0 overview](http://tutorials.jenkov.com/oauth2/overview.html)
2. [OAuth 2.0 in depth](https://code.tutsplus.com/articles/oauth-20-the-good-the-bad-the-ugly--net-33216)
3. [Omniauth github](https://github.com/omniauth/omniauth)
4. [List of stretegies](https://github.com/omniauth/omniauth/wiki/List-of-Strategies)
* [todo1](http://railscasts.com/episodes/241-simple-omniauth-revised)
* [todo2](https://github.com/omniauth/omniauth)
* todo3 : read api documents for twitter or facebook or google map etc
* [additional1](https://stackoverflow.com/questions/6228870/interfacing-with-a-third-party-api-in-rails-opeing-urls-and-parsing-xml-json)
* [additional2](https://www.youtube.com/watch?v=Af5HDgvGuXk)
##### [working with external-api](https://www.theodinproject.com/courses/ruby-on-rails/lessons/working-with-external-apis)
