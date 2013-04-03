!SLIDE center

![Ruby Drawing](images/ruby.png)

!SLIDE center

# POP Builder
## How are we doing?

!SLIDE center

# Data Model
## Anyone want to elaborate?

!SLIDE center

# Performance Assessment
## Show Your skills

!SLIDE bullets center

# Questions

* Live Programming?
* Any issues worth **sharing**?

!SLIDE center

# Nested Forms

!SLIDE

# PlansController

```ruby
class Plan < ActiveRecord::Base
  attr_accessible :user_attributes, :planned_competences_attributes

  belongs_to :user
  accepts_nested_attributes_for :user
end
```

```ruby
class PlansController < ApplicationController
	def new
	  @plan = Plan.new
	  @plan.build_user
	end
end
```

```erb
<%= form_for @plan do |f| %>
	<%= f.fields_for :user do |u| %>
		<%= u.text_field :name %>
	<% end %>
<% end %>
```

!SLIDE center

# Demonstration

!SLIDE center

# Github
## github.com/NHLHogeschool

Download my attempt [here](https://github.com/NHLHogeschool/NextSemester)

Course sheets are [here](https://github.com/NHLHogeschool/Web-Programming)

!SLIDE center

# Seriously
## Think about Questions…
…we are here to help.