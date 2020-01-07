# StatusBarScreen
GZDoom StatusBar functionality under the Screen API.

# Functions
###### DrawTexture
```
	**Takes**
	TextureID texture, 
	Vector2 pos, 
	int flags = 0, 
	double Alpha = 1., 
	Vector2 scale = (1, 1), 
	Color tint=Color(0,0,0,0)
	
	**Returns**
	void
```
###### DrawImage
```
	**Takes**
	String graphic, 
	Vector2 pos, 
	int flags = 0, 
	double Alpha = 1.,
	Vector2 scale = (1, 1), 
	Color tint=Color(0,0,0,0)
	
	**Returns**
	void
```
###### DrawMugshot
```
	**Takes**
	int accuracy, 
	vector2 pos, 
	int drawflags = 0, 
	int mugshotflags = 0, 
	float alpha = 1.0, 
	vector2 scale=(5.0,5.0), 
	string default_face="STF"
	
	**Returns**
	void
```
###### GetImageSize
```
	**Takes**
	String graphic
	
	**Returns**
	vector2
```
###### DrawString
```
	**Takes**
	Font fnt, 
	String str,
	Vector2 pos, 
	int flags = 0, 
	int translation = Font.CR_UNTRANSLATED, 
	double Alpha = 1., 
	Vector2 scale = (1, 1), 
	Color tint = Color(0,0,0,0), 
	int linespacing = 20
	
	**Returns**
	void
```
###### Fill
```
	**Takes**
	Color col, 
	double x, 
	double y,
	double w, 
	double h, 
	int flags = 0
	
	**Returns**
	void
```
###### SetClipRect
```
	**Takes**
	int x, 
	int y, 
	int w, 
	int h
	
	**Returns**
	void
```
###### ClearClipRect()
```
	**Returns**
	void
```