# EduSpace user flow

```text
Open EduSpace
   |
   v
Dashboard ------------------------------+
   |                                    |
   +--> Browse courses --> Course page  |
   |                         |          |
   |                         v          |
   |                    Enroll / Start  |
   |                         |          |
   |                         v          |
   |                    Open lesson     |
   |                         |          |
   |                  Complete lesson   |
   |                         |          |
   |                         v          |
   |                 XP + progress -----+
   |
   +--> Notes --> Create / Search / Delete
   |
   +--> Planner --> Add task --> Mark complete
   |
   +--> Progress --> Review course progress
   |
   +--> Profile --> Edit demo profile
```

## Main success path
A student discovers a course, opens its detail page, enrolls, studies a lesson, marks it complete, and sees progress and XP update.

## Edge cases to test
- Search returns no courses.
- Student has not enrolled in any course.
- Notes list is empty.
- User submits an empty task or note title.
- User refreshes the page after saving data.
- User opens the app on a narrow mobile viewport.
