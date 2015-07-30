SRC='TimeOutHard'

task :build do
  sh "javac #{SRC}.java"
end

task :run do
  sh "java #{SRC}"
end

task :test => [:build, :run] do
  
end

task :clean do
  sh "rm -rf ./*.class"
end
