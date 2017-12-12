## CTF


```ruby

require 'Psych0'

exploit = Psych0.new.inject('localhost, 80')
p exploit.read
```
