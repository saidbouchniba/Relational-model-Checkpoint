# Relational-model-Checkpoint

hotel (hotel_id, hotel_name, #room_id, #employee_id)
type (type_id, type_name, #hotel_id)
employee (epmloyee_id, employee_name, employee_speciality)
room (room_id, floor)
category (category_id, category_name, price, beds_numbers, #room_id)
leads (leads_id, #employee_id)
