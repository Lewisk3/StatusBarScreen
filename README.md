# StatusBarScreen
GZDoom StatusBar functionality under the Screen API.

# Functions
###### DrawTexture
```
	TextureID texture, 
	Vector2 pos, 
	int flags = 0, 
	double Alpha = 1., 
	Vector2 scale = (1, 1), 
	Color tint=Color(0,0,0,0),
	vector2 texoffs = (1,1),
	bool absolute=false
	
	@returns void
```
###### DrawImage
```
	String graphic, 
	Vector2 pos, 
	int flags = 0, 
	double Alpha = 1.,
	Vector2 scale = (1, 1), 
	Color tint=Color(0,0,0,0),
	vector2 texoffs = (1,1),
	bool absolute=false
	
	@returns void
```
###### DrawMugshot
```
	int accuracy, 
	vector2 pos, 
	int drawflags = 0, 
	int mugshotflags = 0, 
	float alpha = 1.0, 
	vector2 scale=(5.0,5.0), 
	string default_face="STF",
	bool absolute=false
	
	@returns void
```
###### GetImageSize
```
	String graphic
	
	@returns vector2
```
###### DrawString
```
	Font fnt, 
	String str,
	Vector2 pos, 
	int flags = 0, 
	int translation = Font.CR_UNTRANSLATED, 
	double Alpha = 1., 
	Vector2 scale = (1, 1), 
	Color tint = Color(0,0,0,0), 
	int linespacing = 20
	
	@returns void
```
###### Fill
```
	Color col, 
	double x, 
	double y,
	double w, 
	double h, 
	int flags = 0
	
	@returns void
```
###### SetClipRect
```
	int x, 
	int y, 
	int w, 
	int h
	
	@returns void
```
###### ClearClipRect()
```
	@returns void
```
# 3D Extended Functions

###### VRotate
```
	vector2 pos,
	vector2 angle,
	bool inverted = false
	
	@returns rotated vector2
```


###### GetActorHUDPos
```
	ViewProjection viewproj,
	Actor onactor,
	double xoffs=0, 
	double yoffs=0,
	double zoffs=0,
	bool rotatecoords=true
	
	@returns 3D actor's projected coords; vector2
```


###### GetActorViewProj
```
	Actor viewer
	
	@returns viewer's view perspective; ViewProjection
```

###### CreateViewProjection
```
	float FOV, 
	vector3 view_position, 
	float viewer_angle, 
	float viewer_pitch, 
	float viewer_roll
	
	@returns ViewProjection
```

###### GetRenderEventViewProj
```
	RenderEvent e, 
	float fov = 90
	
	@returns view perspective from RenderOverlay/UnderLay; ViewProjection
```

###### ProjectToHUD
```
	ViewProjection viewp, 
	vector3 _worldpos, 
	vector3 projoffs
	
	@returns bool infront, vector2 hud_coords
```

###### DrawString3D
```
	Font fnt, 
	String str,
	Vector2 pos, 
	int flags = 0, 
	int translation = Font.CR_UNTRANSLATED, 
	double Alpha = 1., 
	Vector2 scale = (1, 1), 
	Color tint = Color(0,0,0,0), 
	int linespacing = 20
	float distance=0
	
	@returns void
```
