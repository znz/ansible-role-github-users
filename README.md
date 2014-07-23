# znzj.github-users

Setup users with github users' ssh keys.

## Requirements

- OpenSSH Server
- sudo with `/etc/sudoers.d` if enable sudoers

## Role Variables

- `github_users: [ { username: name, sudoers: bool } ]`

## Dependencies

None.

## Example Variables

```
github_users:
- username: firstuser
  sudoers: yes
- username: seconduser
  sudoers: no
- username: youruser
  sudoers: yes
```

## License

MIT
