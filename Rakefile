require "yast/rake"

Yast::Tasks.configuration do |conf|
  conf.obs_api = "https://api.suse.de/"
  conf.obs_target = "SLE-12"
  conf.obs_sr_project = "SUSE:SLE-12:GA"
  conf.obs_project = "Devel:YaST:SLE-12"
  #lets ignore license check for now
  conf.skip_license_check << /.*/
end
