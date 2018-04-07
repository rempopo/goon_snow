# tS_snow
deployable snow particles for missions

**Copy all files to root of the mission folder**

edit description.ext:

```class Params
{   
	class par_snow
	{
	    title = "Let it snow?";
	    values[] = {0,1};
	    default = 1;
	    texts[] = {"no","yes"};
	};
	
// Snowfall music		
	class CfgMusic
	{
		tracks[]={};
		
		class snowfall_music
			{ 
				name = "snowfall"; 
				sound[] = {\sound\snowfall.ogg, db+20, 1.0};
			};	
	};
```
