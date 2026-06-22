# Review Questions

## 1. What is an Alias?

An alias is a shortcut name for a command or group of commands.

## 2. Why are aliases useful?

Aliases save time, reduce typing, and simplify frequently used commands.

## 3. What command displays all aliases?

```bash
alias
```

## 4. What command creates an alias?

```bash
alias ll='ls -l'
```

## 5. What command removes an alias?

```bash
unalias ll
```

## 6. What is the difference between a temporary alias and a permanent alias?

- **Temporary Alias:** Exists only in the current shell session.
- **Permanent Alias:** Stored in a configuration file and available in future sessions.

## 7. Which file is commonly used to store permanent aliases?

```bash
~/.bashrc
```

## 8. What does source ~/.bashrc do?

```bash
source ~/.bashrc
```

Reloads the `.bashrc` file and applies changes without logging out.

## 9. Why should Linux Administrators use aliases?

To improve efficiency, reduce typing, and avoid repetitive commands.

## 10. Give three examples of aliases you would use daily.

```bash
alias ll='ls -l'
alias d='date'
alias c='clear'
```

---

# Lab Summary

In this lab, I learned how to:

- View existing aliases.
- Create temporary aliases.
- Use aliases to simplify commands.
- Delete temporary aliases using `unalias`.
- Create permanent aliases.
- Store aliases in `.bashrc`.
- Reload shell configuration using `source ~/.bashrc`.
- Remove permanent aliases.
- Improve productivity using shortcut commands.

These skills help Linux Administrators work faster and more efficiently in daily system administration tasks.