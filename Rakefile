
task default: :copy_resident_webapp

task :copy_resident_webapp do
    repo = 'rs-webapp-resident'
    system 'rm -Rf public/en/*'
    system "cp -R ../#{repo}/dist/* public/en"
    puts "Copied the resident webapp from '#{repo}'."
end
