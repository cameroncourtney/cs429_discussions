# Syntax of rules with prerequisites:

# final_target: sub_target other_dependencies
# <TAB>recipe_to_create_final_target

# sub_target: other_dependencies
# <TAB>Recipe_to_create_sub_target

# Phony target
# .PHONY: all say_hello generate clean

all: say_hello generate

say_hello:
	@echo "Hello World"

generate:
	@echo "Creating empty text file..."
	touch file.txt

clean:
	@echo "Cleaning up..."
	rm *.txt
