# sw_anim_button


this.button1.setOnTouchListener(new View.OnTouchListener(){ public boolean onTouch(View view, MotionEvent motionEvent) { switch(motionEvent.getAction()) { case 0: { MainActivity.this.button1.setScaleX(0.9f); MainActivity.this.button1.setScaleY(0.9f); return false; } case 1: { MainActivity.this.button1.setScaleX(1.0f); MainActivity.this.button1.setScaleY(1.0f); return false; } case 3: { MainActivity.this.button1.setScaleX(1.0f); MainActivity.this.button1.setScaleY(1.0f); break; 

} 

} return false;

 } 

});
