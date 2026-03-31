CC = gcc

CFLAGS = -Iinclude -Imock -Itest_framework -Wall -Wextra

SRC = src/cmd_line.c
TEST = test/test_cmd_line.c
UNITY = test_framework/unity.c

OUT = test_runner

all:
	$(CC) $(CFLAGS) $(SRC) $(TEST) $(UNITY) -o $(OUT)

run: all
	./$(OUT)

clean:
	rm -f $(OUT)
