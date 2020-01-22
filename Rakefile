task :binary => 'hello.o' do
    sh "gcc hello.o -o hello"
end

task 'hello.o' do
    sh "gcc -c hello.c"
end 

task :default => :binary

