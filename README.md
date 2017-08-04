Simple Ruby on Rails 5 REST API
1. Add gem 'faker'
2. bundle install
3. rails db:migrate
4. create seed files
5.times do 
	Article.create({
		title: Faker::Book.title,
		body: Faker::Lorem.sentence
		})
end

6. rails db:seed

7. You can check files in console
rails c
Article.connection
Article.all
