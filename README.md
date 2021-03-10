Theme inspired by prettydocs-v2.3


Install for RHEL/CentOS/Fedora:

```
sudo dnf install epel-release
sudo dnf install gem
gem install asciidoctor
gem install coderay
```


```
asciidoctor index.html
```


```
cd singletons
asciidoctor python.html
```

```
asciidoctor --destination-dir output/ singletons/python.adoc
```

```
asciidoctor --destination-dir output/ index.adoc
```