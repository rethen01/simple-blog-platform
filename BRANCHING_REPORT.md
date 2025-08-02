# Branching Report

## Merge Statistics
- Total number of merges: 4
- Fast-forward merges: 1
- 3-way merges: 3
- Merges with conflicts: 1

## Branch History
   67b6532 (HEAD -> main, origin/main) Merge branch 'documentation'
|\
| * afc4d10 (documentation) Update README.md
|/
*   df6f966 Merge feature/header-update with conflict resolution
|\
| * 8825694 Update header to v2.0
* | 2a0a4d4 Customize blog title
|/
*   47bea5f Merge branch 'feature/design'
|\
| * 023611f Improve design and add navigation
* |   c3de453 Merge branch 'feature/comments'
|\ \
| * | 002a9e3 Add comments section
| |/
* / f19bb41 Change Readme for 3-way merge
|/
* bd08f3e Add posts page and functionality
* e725402 Initial project setup
## Lessons Learned
Используется 2 типа слияния. FF - переносит коммитыповерх ветки в которую вливается. При 3-way merge - возможны конфликты, из-за которых не выполняется сливания. Разрешить возможно изменив файлы, git подсвечивает их указателями и описанием ветки.

