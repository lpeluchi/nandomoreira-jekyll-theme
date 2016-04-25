---
layout: post
title: "Active Record Association"
date: 2016-04-25
categories: 
keywords:
description: "Active Record Associations"
comments: true
categories:
- welcome
tags:
- welcome
- hello-world

---

Active record associations are a connection between two active records. They’re useful because they allow the user to get data through interacting with the data as if it’s a Ruby object instead of using all of the SQL statements. This makes it much easier and more straightforward for programmers to request data and to keep track of all the different relationships they have between their data.

With this, there are different types of associations possible. One of them is belongs_to. This one will connect models with a one-to-one connection meaning that one instance of a model only belongs to one other instance in a different model. The has_one connection is another possibility. Like the belongs_to connection, this one is also a one-to-one connection, but in this case it means that an instance in a model possesses an instance in a different model. Another connection is the has_many connection, which is a one-to-many connection. This one works with the belongs_to connection because it says that one instance of a model either has no instances or many instances in another model. The last connection, for now, is the has_and_belongs_to_many, which is a many-to-many connection, like the join tables from before, which you still need to create when using active record association.

The belongs_to connection and the rest of the associations work together because if you’re connecting two things together, one will have the belongs_to connection while the other one will have one of the other connections. Deciding which one should have the belongs_to association depends on which data should be possessed by the other data versus which should own data. When making these associations, it’s important to think about which instances or models should be plural, otherwise you might run into problems with the code. Another thing to be careful of is making sure that your association relates to the foreign key in your table, or if it doesn’t correspond, that you make that clear and tell the program what the foreign key is.

http://guides.rubyonrails.org/association_basics.html
http://www.theodinproject.com/ruby-on-rails/active-record-basics http://www.theodinproject.com/ruby-on-rails/active-record-associations
http://www.tutorialspoint.com/ruby-on-rails/rails-models.htm
http://culttt.com/2015/10/21/understanding-active-record-associations/
