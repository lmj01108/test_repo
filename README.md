# team_project_test

# whlile run
        
        if Game_Over:
            screen.fill((255,255,255))    
            game_over_image1 = Big_font.render('Game Over', True, (255,0,0))
            game_over_image2 = Small_font.render('Score: {}'.format(score), True, (255, 245, 0))
            screen.blit(game_over_image1, (WIDTH - game_over_image.get_width()//2, HEIGHT - game_over_image.get_height()//2 ))
            screen.blit(game_over_image2, (WIDTH - game_over_image.get_width()//2, (HEIGHT - game_over_image.get_height()//2)-10 ))

        pygame.display.update()
        clock.tick(50) #초당 프레임 수 
        
    pygame.quit()
