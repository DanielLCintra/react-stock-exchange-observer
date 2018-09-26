task :default do
    sh "rake -T"
end

desc "To build project container"
task :build_container do
    sh "docker image build -t react:app ."
end

desc "To run project in development mode"
task :run_dev do
    sh "docker container run -it -p 3000:3000 -p 35729:35729 -v $(pwd):/app react:app"
end

desc "To build project"
task :run_build do
    sh "docker container run -it -v $(pwd):/app react:app build"
end

desc "To run tests"
task :run_test do
    sh "docker container run -it -v $(pwd):/app react:app test"
end





