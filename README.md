### ECR Options

- Mutable : 이미지 태그를 덮어쓸 수 있습니다.
- Immutable : 이미지 태그를 덮어쓸 수 없습니다.

```
├── Dockerfile
├── README.md
├── app.go
├── immutable
│   └── buildspec.yml
└── mutable
    └── buildspec.yml
```
