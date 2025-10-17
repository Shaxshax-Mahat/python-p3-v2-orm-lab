# TODO List for ORM Lab Implementation

## 1. Implement ORM Methods in Review Class (lib/review.py)
- [ ] Implement `save()` method: Insert new row into reviews table, set id, add to all dict
- [ ] Implement `create()` class method: Instantiate Review and call save()
- [ ] Implement `instance_from_db()` class method: Check all dict, create/update instance
- [ ] Implement `find_by_id()` class method: Query by id, return instance or None
- [ ] Implement `update()` method: Update row with current attributes
- [ ] Implement `delete()` method: Delete row, remove from dict, set id to None
- [ ] Implement `get_all()` class method: Query all rows, return list of instances

## 2. Add Property Methods to Review Class
- [ ] Add `year` property: Validate int >= 2000
- [ ] Add `summary` property: Validate non-empty string
- [ ] Add `employee_id` property: Validate int and Employee exists in DB

## 3. Implement reviews() in Employee Class (lib/employee.py)
- [ ] Add `reviews()` instance method: Query reviews by employee_id, return list of Review instances

## 4. Followup Steps
- [ ] Run `pytest lib/testing/review_orm_test.py`
- [ ] Run `pytest lib/testing/review_property_test.py`
- [ ] Run `pytest lib/testing/employee_orm_test.py`
- [ ] Ensure all tests pass
