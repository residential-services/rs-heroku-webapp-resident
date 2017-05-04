
task default: :copy_resident_webapp

task :copy_resident_webapp do
    source_repo = 'rs-webapp-resident'
    dest_folder = 'public/en/resident'
    system "rm -Rf '#{dest_folder}/*'"
    system "cp -R '../#{source_repo}/dist'/* '#{dest_folder}'"
    puts "Copied the resident webapp from '#{source_repo}'."
end
