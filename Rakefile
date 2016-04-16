task :build do
  sh "bundle exec middleman build"
end

task deploy: :build do
  sh "firebase deploy"
end
