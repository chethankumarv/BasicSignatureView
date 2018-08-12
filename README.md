# BasicSignatureView

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories.


    allprojects {
	     	repositories {
		    	...
		   	  maven { url 'https://jitpack.io' }
		    }
	    }
  
  
  Step 2. Add the dependency.
  
  
  	dependencies {
	        implementation 'com.github.chethankumarv:BasicSignatureView:master'
	}
  
  
  
  Step 3.
  Add in your MainActivity after setContentView(R.layout.activity_main); like below in onCreate method
  
  
    setContentView(R.layout.activity_main);
    SignatureDrawingView signatureDrawingView = new SignatureDrawingView(this);
   
   
   
   Step 4.
   Add the below view in activity_main.xml
   
    <signatureview.xolcano.com.signatureviewlibrary.SignatureDrawingView
        android:layout_width="match_parent"
        android:layout_height="match_parent" />
        
        
ENJOY....!!!!
