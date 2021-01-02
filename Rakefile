# frozen_string_literal: true

desc 'Compile LaTeX files'
task :tex do
  cd 'tex'
  sh 'latexmk', '-cd'
end

namespace :tex do
  task :clean do
    cd 'tex'
    sh 'latexmk', '-cd', '-C'
  end
end

task default: :tex
