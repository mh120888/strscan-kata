guard 'rspec', cmd: "bundle exec rspec -f p" do
  watch('lib/josh_strscan.rb')        { 'spec/josh_strscan_spec.rb' }
  watch('spec/spec_helper.rb')        { 'spec' }
  watch('spec/acceptance_spec.rb')    { 'spec/acceptance_spec.rb' }
  watch('spec/josh_strscan_spec.rb')  { 'spec/josh_strscan_spec.rb' }
end