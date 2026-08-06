# Task 02 - Hard Link and Soft Link

## Objective

Understand the difference between Hard Link and Soft Link in Linux.

## Commands Used

### Hard Link

```bash
ln IT/servers.txt Hard_Link_of_Servers
```

### Soft Link

```bash
ln -s Sales/clients.txt Soft_Link_of_clients
```

### Verify

```bash
ls
cat Hard_Link_of_Servers
cat Soft_Link_of_clients
```

## Output

Successfully created both Hard Link and Soft Link.

## Difference

| Hard Link | Soft Link |
|------------|------------|
| Shares the same inode as the original file | Has a different inode |
| Works only within the same filesystem | Can point to another filesystem |
| Still works if the original filename is removed | Breaks if the original file is deleted |

## Screenshots

- `screenshots/Hard_Link.png`
- `screenshots/Soft_Link.png`

## What I Learned

- How to create Hard Links.
- How to create Symbolic (Soft) Links.
- The functional differences between them.