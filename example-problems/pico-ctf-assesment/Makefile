.PHONY: main
main: flag

FLAG := "picoCTF{sur_download}"

artifacts.tar.gz: flag.txt
	tar czvf $@ $^

flag:
	@echo "$(FLAG)" > flag.txt

metadata.json:
	@echo "Creating the metadata file..."
	@echo "{\"flag\":\"$(FLAG)\"}" > metadata.json

clean:
	rm -f flag
