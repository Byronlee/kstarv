guard :rspec do
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^lib/(.+)\.rb$}) { 'spec' }
  watch('spec/spec_helper.rb')  { "spec" }
  watch(%r{^spec/factories/(.+)_factory\.rb$}){ "factories" }
end

