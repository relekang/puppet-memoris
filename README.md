# puppet-memoris

Deploy the memoris api with puppet. Set up a redis-server if wanted

```puppet
class{ 'memoris':
  redis_port        => 6379,
  redis_host        => '127.0.0.1',
  configurate_redis => true
}
```
