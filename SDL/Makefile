all: buildSubDir

PWD_DIR=$(PWD)

SUB_DIRS=01 02 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36

buildSubDir:
	echo Pwd = $(PWD_DIR)
	@for i in $(SUB_DIRS) ; do \
		cd $$i; \
		echo "────────────────────────" ; \
		echo "Compiling '$$i' directory" ; \
		echo "────────────────────────" ; \
		$(MAKE) all; \
		cd $(PWD_DIR);  \
	done

clean:
	@for i in $(SUB_DIRS) ; do \
		cd $$i; \
		echo "────────────────────────" ; \
		echo "Cleaning '$$i' directory" ; \
		echo "────────────────────────" ; \
		$(MAKE) clean; \
		cd $(PWD_DIR);  \
	done

realclean:
	@for i in $(SUB_DIRS) ; do \
		cd $$i; \
		echo "────────────────────────" ; \
		echo "Real Cleaning '$$i' directory" ; \
		echo "────────────────────────" ; \
		$(MAKE) realclean; \
		cd $(PWD_DIR);  \
	done
