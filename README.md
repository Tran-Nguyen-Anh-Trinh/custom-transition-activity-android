# custom-transition-activity-android

START ACTIVITY

  startActivity(Intent(this, SecondActivity::class.java))
  
  overridePendingTransition(R.anim.slide_in_from_right, R.anim.slide_out_to_left);
  
FINISH ACTIVITY

  finish()
  
  overridePendingTransition(R.anim.slide_in_from_left, R.anim.slide_out_to_right);
