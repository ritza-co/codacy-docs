# Specifying your Python version

Although our tools try to detect which Python version your repository uses, some false positives may occur.

To instruct which Python version you want Codacy to use, you can define the following in a [Codacy configuration file](codacy-configuration-file.md) added in the root of your repository - `.codacy.yml`:

```yaml
---
engines:
  pylint:
    enabled: true
    python_version: 2
```

Supported versions: 2, 3

Supported tools: [codacy-pylint](https://github.com/codacy/codacy-pylint)
