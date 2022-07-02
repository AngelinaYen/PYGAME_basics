# PYTHON GAMES: 利用 Pygame module 自己創造的小遊戲

1. **參考資料**
  1. Pygame Page: http://pygame.org
  2. documentation: https://www.pygame.org/news
  3. IconArchive: https://iconarchive.com/  (下載遊戲角色)
  4. Leshy SFMaker: https://www.leshylabs.com/apps/sfMaker (下載音效)
  5. ~~多出的一行，示範廢話~~ <br><br>
 ------

**_2. What is Pygame_**:
  * Pygame提供Display, Sound, Image, Text, Event幫助製作遊戲
  * Pygame可以做出2-D小遊戲
  * Pygame偵測使用者使用Keyboard, joystick, mouse控制遊戲
  * Pygame提供許多內建的gameobjects來製作遊戲

**_3. PYGAME Basics_**:
| name | Desciption |
|:-----:|:----------:|
| _1.py_ | Create my game surface, game loop and drawing.|
| _2.py_ | Blit text, font, sound and image objects.   |
| _3.py_ | Getting user keyboard and collision dection.|

**_4. Code snippet_**
```python
# Create game display
WINDOW_WIDTH, WINDOW_HEIGHT = 1000, 600
displayscreen = pygame.display.set_mode((WINDOW_WIDTH, WINDOW_HEIGHT))
pygame.display.set_caption("Feed the Angry Bird")
```

```python
# Blite image object and setting its rec
player_image = pygame.image.load("angry_bird.png")
player_rect = player_image.get_rect()
player_rect.left = 32
player_rect.centery = WINDOW_HEIGHT//2
displayscreen.blit(player_image, player_rect)
```
**_5. Game Assets:_** <br>
    * [Icon Archive:](https://iconarchive.com/)網站提供很多遊戲角色下載
    * [Leshy SFMaker:](https://www.leshylabs.com/apps/sfMaker/)網站可以下載遊戲特效，也可以自己簡單製作音效
    
    
    
    
    
    
