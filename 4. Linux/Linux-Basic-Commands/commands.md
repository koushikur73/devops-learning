# Linux Basic Commands

This document contains the basic Linux commands I learned and practiced during Day 04 of my DevOps learning journey.

---

## 1. ls

**Description:** Lists files and directories.

**Syntax**

```bash
ls
```

**Example**

```bash
ls
ls -l
ls -la
```

---

## 2. cat

**Description:** Displays the contents of a file.

**Syntax**

```bash
cat filename
```

**Example**

```bash
cat employees.txt
```

---

## 3. mkdir

**Description:** Creates a new directory.

**Syntax**

```bash
mkdir directory_name
```

**Example**

```bash
mkdir company
mkdir HR
```

---

## 4. clear

**Description:** Clears the terminal screen.

**Syntax**

```bash
clear
```

---

## 5. echo

**Description:** Prints text or writes data into a file.

**Syntax**

```bash
echo "text"
```

**Example**

```bash
echo "Hello Linux"
echo "101,Koushik,IT" >> employees.txt
```

---

## 6. touch

**Description:** Creates an empty file.

**Syntax**

```bash
touch filename
```

**Example**

```bash
touch employees.txt
```

---

## 7. rm

**Description:** Removes files or directories.

**Syntax**

```bash
rm filename
```

**Example**

```bash
rm clients.txt
rm -r company
```

---

## 8. mv

**Description:** Moves or renames files and directories.

**Syntax**

```bash
mv source destination
```

**Example**

```bash
mv employees.txt employee_list.txt
mv employee_list.txt HR/
```

---

## 9. cut

**Description:** Extracts specific columns from a file.

**Syntax**

```bash
cut -d "," -f2 filename
```

**Example**

```bash
cut -d "," -f2 employees.txt
```

---

## 10. tee

**Description:** Writes output to both the terminal and a file.

**Syntax**

```bash
tee filename
```

**Example**

```bash
echo "Linux" | tee notes.txt
```

---

## 11. Hard Link

**Description:** Creates another reference to the same file.

**Syntax**

```bash
ln source_file hard_link_name
```

**Example**

```bash
ln IT/servers.txt Hard_Link_of_Servers
```

---

## 12. Soft Link

**Description:** Creates a symbolic link to another file.

**Syntax**

```bash
ln -s source_file soft_link_name
```

**Example**

```bash
ln -s Sales/clients.txt Soft_Link_of_Clients
```

---

## 13. wc

**Description:** Counts lines, words, and characters.

**Syntax**

```bash
wc filename
```

**Example**

```bash
wc employees.txt
```

---

## 14. sort

**Description:** Sorts the contents of a file alphabetically.

**Syntax**

```bash
sort filename
```

**Example**

```bash
sort developers.txt
```

---

## 15. diff

**Description:** Compares two files line by line.

**Syntax**

```bash
diff file1 file2
```

**Example**

```bash
diff employees.txt salary.txt
```

---

## 16. head

**Description:** Displays the first 10 lines of a file by default.

**Syntax**

```bash
head filename
```

**Example**

```bash
head employees.txt
```

---

## 17. tail

**Description:** Displays the last 10 lines of a file by default.

**Syntax**

```bash
tail filename
```

**Example**

```bash
tail employees.txt
```

---

## 18. less

**Description:** Opens a file for interactive viewing.

**Syntax**

```bash
less filename
```

**Example**

```bash
less employees.txt
```

### Navigation

- `↑` / `↓` → Scroll
- `Space` → Next page
- `b` → Previous page
- `q` → Quit

---

## 19. more

**Description:** Displays file content one page at a time.

**Syntax**

```bash
more filename
```

**Example**

```bash
more employees.txt
```

### Navigation

- `Space` → Next page
- `Enter` → Next line
- `q` → Quit

---

# Commands Learned

- ls
- cat
- mkdir
- clear
- echo
- touch
- rm
- mv
- cut
- tee
- ln
- ln -s
- wc
- sort
- diff
- head
- tail
- less
- more