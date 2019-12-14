# Requirements 👀

- bash 4.0 or higher
- curl

# Install ⚙️

``` bash
curl -o is-wordpress https://raw.githubusercontent.com/tanrax/is-wordpress/master/is-wordpress
chmod +x is-wordpress
sudo mv is-wordpress /usr/local/bin
```

# Run 🏃‍♂️ 

``` bash
is-wordpress [domain]
```

# Example 👨‍🎓

``` bash
is-wordpress blog.us.playstation.com
```
⬇️
``` bash
true
```
---

``` bash
is-wordpress google.com
```
⬇️
``` bash
false
```

