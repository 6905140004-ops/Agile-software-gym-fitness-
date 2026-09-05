# Database Design

## Users
- user_id (PK)
- name
- email
- fitness_level

## Gyms
- gym_id (PK)
- gym_name
- address
- opening_hours
- membership_price

## Activities
- activity_id (PK)
- activity_name
- category
- description
- duration_minutes
- cost
- fitness_level

## WorkoutPlans
- plan_id (PK)
- plan_name
- fitness_level
- estimated_time

## Exercises
- exercise_id (PK)
- plan_id (FK)
- exercise_name
- instruction
