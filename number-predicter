import random

score = 0
right_to_guess = 0
random_number = random.randint(1,10)

while right_to_guess < 5:
    try:
        guess = int(input("Bir sayı girin: "))
        
        right_to_guess += 1
        
        if right_to_guess == 5:
            print(f"Hakkınız bitti! Cevap {random_number} sayısıydı.")
            break   
          
        
        if guess < random_number:
            print("Yukarı!")
                
        elif guess > random_number:
            print("Çok oldu, aşağı!")
                
        else:
            score  = (100-((right_to_guess)*20))
            if right_to_guess == 1:
                print(f"Doğru cevap {guess} tebrikler! {right_to_guess} hak kullandınız. Puanınız 100.")   
            else:
                print(f"Doğru cevap {guess} tebrikler! {right_to_guess} hak kullandınız. Puanınız {score}")
            break
        
        
    except ValueError:
        print("Lütfen geçerli bir değer girin.")