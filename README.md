This model can be used to define a custom user model for Django auth user.

Most Straightforward way is to copy the whole content of CustomUserModel.py to your models.py and add the following to your settings.py

AUTH_USER_MODEL = 'yourappcontainingcustomusermodel.User'
