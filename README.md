# Twini-Golf

Twini-Golf is a game created for two players to par different holes 
![alt text](image.png)
Thử nghiệm game:

#Giới thiệu game
Với mục tiêu để tạo ra một con game mang thiên hướng mini golf nhưng tăng độ khó khi phải điều khiển một lúc hai bóng với hai stage có chướng ngại vật khác nhau. Ban đầu game có ý định cho một người chơi nhưng khi cải tiến game sẽ dành cho hai người chơi và đếm số gậy mỗi level hoặc tổng số gậy để phân thắng bại.

# Windows
Sau khi cài đặt môi trường Mingw64, SDL2, SDL_Image, SDL_TTF, and SDL_Mixer.

![alt text](image-1.png)
File .exe sẽ ở trong mục ./bin. Để game chạy cần copy ./res folder và các .dll files từ trong thư viện SDL.

# Bắt đầu game
![alt text](image-2.png)
Màn hình khởi động game có thể bấm bất cứ vị trí nào trên màn hình để khởi động
![alt text](image-3.png)
Người chơi sẽ luân phiền nhau đưa các bóng của mình vào lỗ và đồng thời hai bóng sẽ di chuyển nên chiến thuật sẽ là để bóng mình vào lỗ nhanh nhất nhưng cũng làm chậm quá trình đưa bóng vào lỗ của đối phương 
![alt text](image-4.png)
Xong khi hai bóng đều vào lỗ trò chơi sẽ tự động đổi sang level khác và chướng ngại vật cũng sẽ thay đổi
![alt text](image-5.png)
Khi kết thúc màn hình sẽ hiện lên số gậy mỗi người chơi sử dụng trong mỗi màn có thể so tổng số gậy hoặc tổng số màn thắng 

# Game resource
Game texture:
![alt text](tile64_dark.png) 
![alt text](tile64_light.png)
![alt text](tile32_dark.png)
![alt text](tile32_light.png)
Các chướng ngại vật của game

![alt text](bg.png)
Background của game
![alt text](ball.png)
Quả bóng 
![alt text](point.png)
Công cụ điều hướng bóng 

