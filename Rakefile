task :default => :rps

desc "Run rps_simple_command_line.rb.rb with ruby. Visit localhost//throw/scissors"
task :rps do
  sh "ruby rps_simple_command_line.rb.rb"
end

desc "Run rps_simple_command_line.rb.rb with debugger"
task :debug do
  sh "ruby -rdebug rps_simple_command_line.rb.rb"
end

desc "makes a tar.gz with the files"
task :tar do
  sh "tar  cvzf rockpaperscissors.tar.gz *.rb README Rakefile"
end

