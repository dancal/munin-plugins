git clone https://github.com/jzawodn/perl-Redis.git

ln -s /usr/share/munin/plugins/redis_speed_ redis_speed_127_0_0_1_8000
ln -s /usr/share/munin/plugins/redis_speed_ redis_speed_127_0_0_1_8001


ln -s /usr/share/munin/plugins/redis_ redis_connected_clients_127_0_0_1_8000
ln -s /usr/share/munin/plugins/redis_ redis_used_memory_127_0_0_1_8000
ln -s /usr/share/munin/plugins/redis_ redis_keys_per_sec_127_0_0_1_8000

/*
keys_per_sec
key_ratio
per_sec
used_memory
used_keys
*/
