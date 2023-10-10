
PROJDIR := ..
SOURCEDIR := $(PROJDIR)/source
BUILDDIR := $(PROJDIR)/build

SORTS = $(SOURCEDIR)/sorts
UTILS = $(SOURCEDIR)/utils/*.c 

POSFIX = _sort.exe

COMPILER = gcc

all:
	$(COMPILER) -Ofast $(UTILS) $(SORTS)/bubble_sort.c -o bubble$(POSFIX)
	$(COMPILER) -Ofast $(UTILS) $(SORTS)/insertion_sort.c -o insertion$(POSFIX)
	$(COMPILER) -Ofast $(UTILS) $(SORTS)/selection_sort.c -o selection$(POSFIX)
	$(COMPILER) -Ofast $(UTILS) $(SORTS)/heap_sort.c -o heap$(POSFIX)
	$(COMPILER) -Ofast $(UTILS) $(SORTS)/merge_sort.c -o merge$(POSFIX)
	$(COMPILER) -Ofast $(UTILS) $(SORTS)/quick_sort.c -o quick$(POSFIX)

