rpminfo_SOURCES = \
	main.go

all: rpminfo

rpminfo: $(rpminfo_SOURCES)
	go build -x -o rpminfo $(rpminfo_SOURCES)

install:
	go install -x github.com/mstg/go-rpm/cmd/rpminfo

clean:
	go clean -x -i

.PHONY: all install clean
