# a-1

a-0.1.0.0 that exposes nothing.

# a-2

a-0.2.0.0 that exposes A.

# b

b-0.1.0.0 that exposes A if it's configured with a-1 but expose nothing with a-2.

# c

c-0.1.0.0 that uses A from a-2 or b depending on the current installation.
