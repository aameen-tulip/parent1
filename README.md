# Parent1

An example of git submodules.
This repo has 3 child repositories in its tree.

Two being direct children: `child1` and `child2`; and one which is a
grand-child, `child3`, under `child1`.

```sh
$ tree
.
├── README.md
├── child1
│   ├── README.md
│   └── child3
│       └── README.md
└── child2
    └── README.md

3 directories, 4 files
```
