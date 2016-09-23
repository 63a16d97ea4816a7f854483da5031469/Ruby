#Current file absolute Path

puts "current file absolute path:"+File.expand_path(File.dirname(File.dirname(__FILE__)))
puts "current file under folder:"+ File.expand_path("..", Dir.pwd)
