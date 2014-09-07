opt_param.rb
============

def greeting(name, options = {})
	if options.empty?
		puts "hi, my name is #{name}"
	else
		puts "hi, my name is #{name} and i'm #{options[:age]}" +
		" years old and i live in #{options[:city]}."
	end
end

greeting('bob')
greeting('bob', age: 62, city: 'nyc')
