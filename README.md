# StatusBarScreen
GZDoom StatusBar functionality under the Screen API.

# Functions
* DrawTexture(TextureID texture, Vector2 pos, int flags = 0, double Alpha = 1., Vector2 scale = (1, 1))
* DrawImage(String graphic, Vector2 pos, int flags = 0, double Alpha = 1., Vector2 scale = (1, 1))
* DrawString(Font fnt, String str, Vector2 pos, int flags = 0, int translation = Font.CR_UNTRANSLATED, double Alpha = 1., Vector2 scale = (1, 1), int linespacing = 20)
* Fill(Color col, double x, double y, double w, double h, int flags = 0)
* SetClipRect(int x, int y, int w, int h)
* ClearClipRect()