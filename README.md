# StatusBarScreen
GZDoom StatusBar functionality under the Screen API.

# Functions
## DrawTexture
```
	TextureID texture, 
	Vector2 pos, 
	int flags = 0, 
	double Alpha = 1., 
	Vector2 scale = (1, 1), 
	Color tint=Color(0,0,0,0)
	
	@returns void
```
## DrawImage
```
	String graphic, 
	Vector2 pos, 
	int flags = 0, 
	double Alpha = 1.,
	Vector2 scale = (1, 1), 
	Color tint=Color(0,0,0,0)
	
	@returns void
```
## DrawMugshot
```
	int accuracy, 
	vector2 pos, 
	int drawflags = 0, 
	int mugshotflags = 0, 
	float alpha = 1.0, 
	vector2 scale=(5.0,5.0), 
	string default_face="STF"
	@returns void
```
## GetImageSize
```
	String graphic
	@returns vector2
```
## DrawString
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
## Fill
```
	Color col, 
	double x, 
	double y,
	double w, 
	double h, 
	int flags = 0
	@returns void
```
## SetClipRect
```
	int x, 
	int y, 
	int w, 
	int h
	@returns void
```
## ClearClipRect()
```
	@returns void
```