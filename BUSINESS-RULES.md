# Business Rules 

## Animal -> Aggregate

1. An animal must be unique (with an identifier).
2. An animal can have a birthdate that is not known.
3. An animal must belong to exactly one species.
4. An animal is female or male or unknown as sex.
5. An animal can be alive or dead.
6. An animal's birthplace and country of birth can be unknown.
7. A chipnumber can only have one animal.

## Species -> Entity

1. A species can have a subspecies, but a subspecies must belong to a species.
2. A species must be unique (with an identifier).
3. A species must have a conservation status. Extinct, Extinct in the wild, critically endangered, endangered, vulnerable, near threatened, least concern, data deficient and not evaluated.
4. A species can have a scientific name.
5. A species belongs to exactly one animal category.