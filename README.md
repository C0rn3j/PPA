# PPA
God-forsaken place

## Notes

```bash
cp ~/Downloads/gtk4-layer-shell-noble-amd64/*.deb incoming/

for file in incoming/*.deb; do
	reprepro includedeb noble "$file"
done

reprepro export noble
reprepro list noble

```
