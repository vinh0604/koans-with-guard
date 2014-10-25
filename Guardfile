guard 'shell' do
  watch(/(.*)\.rb/) { |m| system("ruby #{m[1]}.rb") }
end
