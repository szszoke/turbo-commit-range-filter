```bash
npx turbo build --filter="...[e74874a]" --dry=json | jq .packages
turbo 2.0.12

[
  "@turbo-commit-range-filter/b"
]
```