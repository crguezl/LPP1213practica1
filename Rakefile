task :default => :rps

desc "Run rps_simple_command_line.rb with ruby. Visit localhost//throw/scissors"
task :rps do
  sh "ruby rps_simple_command_line.rb scissors"
end

desc "Run rps_simple_command_line.rb with debugger"
task :debug, :player do |t, args|
  player = args[:player] || 'scissors'
  sh "ruby -rdebug rps_simple_command_line.rb #{player}"
end

desc "makes a tar.gz with the files"
task :tar do
  sh "tar  cvzf rockpaperscissors.tar.gz *.rb README Rakefile"
end

