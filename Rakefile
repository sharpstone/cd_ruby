
task "assets:precompile" do
  out = `cd client && ruby -v`
  unless $?.success?
    puts "Failed: #{out}"
    exit 1
  end
end
