
task "assets:precompile" do
  out = `cd client && bundle exec ruby -v`
  puts "cd version #{out}"
  unless $?.success?
    puts "Failed: #{out}"
    exit 1
  end
end
