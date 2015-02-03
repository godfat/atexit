
task :test do
  sh 'ruby -S rake foo'
end

task :foo do
  at_exit { print "foobar" }
end
