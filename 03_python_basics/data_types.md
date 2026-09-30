# Python Data Types

str                  → text / string
int                  → whole number
float                → decimal number
bool                 → True or False
None                 → represents no value
bytes                → sequence of bytes
list                 → ordered, mutable collection
tuple                → ordered, immutable collection
dict                 → key-value collection
set                  → unordered collection of unique values
datetime             → date and time value

## Type Checking

type(value)                  → return the data type of a value
isinstance(value, type)     → check if a value is a specific type

## Type Conversion

str(value)           → convert to string
int(value)           → convert to integer
float(value)         → convert to float
bool(value)          → convert to boolean
list(value)          → convert to list
tuple(value)         → convert to tuple
set(value)           → convert to set

## Common Examples
name = "John"                       → str
age = 27                            → int
price = 19.99                       → float
is_active = True                    → bool
result = None                       → NoneType
data = b"hello"                     → bytes
numbers = [1, 2, 3]                 → list
coordinates = (10, 20)              → tuple
user = {"id": 1, "name": "John"}    → dict
unique_ids = {1, 2, 3}              → set

## Data Engineering
None                 → commonly represents a missing/null value
datetime             → used for timestamps and time-based data
str                  → commonly used for IDs, names, and text fields
int / float          → commonly used for numeric data
list / dict          → commonly used when processing JSON/API data
bytes                → used for binary data and file/network operations