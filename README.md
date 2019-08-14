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
+ Additional : [Deorator](https://samuelmullen.com/2011/12/sending-notifications-using-decorators-instead-of-callbacks/)

##### [Wiki callbacks](https://en.wikibooks.org/wiki/Ruby_on_Rails/ActiveRecord/Callbacks)
