# Pine-Ch-04-Mixing-It-Up

# Greeter
puts 'What is your first name?'
fname = gets.chomp.to_s
puts 'What is your last name?'
lname = gets.chomp.to_s
puts 'Do you have a middle name?'
mname = gets.chomp.to_s
puts 'Hello '+fname+' '+mname+' '+lname+'!'

# Favourite number +1
puts 'What is your favourite number?'
favnum = gets.chomp.to_i
bignum = favnum + 1
puts 'I think ' + bignum.to_s + ' is a better number.'
