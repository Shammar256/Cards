class Course(models.Model):
    course_name = models.CharField(max_length=20)
    faculty = models.CharField(max_length=50)
    course_code = models.CharField(max_length=20)
    duration = models.CharField(max_length=20)
    def __str__(self):
        return self.course_name
