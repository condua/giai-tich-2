 \documentclass[a4paper,12pt]{article}
\usepackage[utf8]{vietnam}
\usepackage{amsmath}
\usepackage{graphics}
\usepackage{amsfonts}
\usepackage{amssymb}
\usepackage{hyperref}



\title{}

\author{NGUYỄN PHƯƠNG THANH VI}

\date{March 2021}

\begin{document}

\maketitle
\chapter{CHƯƠNG 16: GRADIENT, GIÁ TRỊ CỰC TRỊ , VI PHÂN}
 
 
 
 
 
 
 
 
 \section{Phần bài tập}
        \begin{enumerate}
            
           
             
            
                   \textbf{26) Bán kính của 1 hình trụ tròn đang giảm ở mức 2 cm/s và chiều cao đang tăng ở mức 3 cm/s. Hãy tính tốc độ thay đổi của thể tích hình trụ tròn khi R = 13cm và h = 18cm.}
                    \\ \textbf{Bài làm}
                   
                    \\ Theo đề bài, ta có:  ${\frac{dr}{dt} }$ =-2(cm/s) và  ${\frac{dh}{dt} }$ = 3(cm/s)
                    \\
                    \\Thể tích hình trụ tròn: V=$\Pi$$r^2$h (1)

                    \\

                    \\Lấy đạo hàm hai vế của (1) ta được:
                    \\
                    \\${\frac{dV}{dt} }$=${\frac{dV}{dr} }$ x ${\frac{dr}{dt} }$ +   ${\frac{dV}{dh} }$x ${\frac{dh}{dt} }$ 
                    \\
                    \\<=>${\frac{dV}{dt} }$=2$\Pi$rhx${\frac{dr}{dt} }$ + $\Pi$$r^2$${\frac{dh}{dt} }$ 
                    \\
                    \\<=>${\frac{dV}{dt} }$=2$\Pi$x13x18x(-2) + $\Pi$x$13^2$x3
                    \\
                    \\<=>${\frac{dV}{dt} }$=-429$\Pi$ ($cm^3$/s)
                    \\
                    \\Vậy thể tích hình trụ tròn sẽ giảm với tốc độ là 429$\Pi$ ($cm^3$/s)
                    \\
                    \\
                    
                    \textbf{27) Nếu độ dài hai cạnh của 1 tam giác là x, y, và θlà góc giữa 2 cạnh đó thì diện tích của tam giác được tính bằng  ${\frac{1}{2} }$xysin($\theta$). Nhìn hình bên dưới. Nếu mỗi cạnh của 2 cạnh này tăng lên với tốc độ là 3 inch/s và $\theta$ giảm với tốc độ là 0.10 radian/s thì tốc độ thay đổi của diện tích khi x=1.5 feet, y=2 feet, $\theta$ =1 radian là bao nhiêu ?}
                    \\
                    \\
                    
                    \textbf{28) Một vật thể di chuyển dọc theo đường cong là giao nhau giữa mặt paraboloid z =$x^2$ +${\frac{1}{4} }$$y^2$ và mặt trụ tròn $x^2$+$y^2$=13. Nếu tọa độ x tăng với tốc độ 5 cm/s thì tốc độ thay đổi của z khi x=2 cm  và y=3 cm là bao nhiêu ?}
                   
                    \\
                    \\ \textbf{Bài làm}
                    \\ 
                    \\Theo đề bài, ta có: ${\frac{dx}{dt} }$=5(cm/s)
                    \\Vật thể di chuyển dọc theo đường cong là giao nhau giữa mặt paraboloid z =$x^2$  + ${\frac{1}{4} }$$y^2$ và mặt trụ tròn $x^2$+$y^2$=13 nên ta có: 
                    \\z = $x^2$ + ${\frac{1}{4} }$(13-$x^2$)=${\frac{3}{4} }$x$x^2$+${\frac{13}{4} }$(1)
                    \\ Lấy đạo hàm hai vế của (1) ta được:
                    \\
                    \\${\frac{dz}{dt} }$=${\frac{dz}{dx} }$ x ${\frac{dx}{dt} }$ = ${\frac{3}{4} }$ x 2x x ${\frac{dx}{dt} }$=${\frac{3}{4} }$x2x2x5=15 ($cm^2$/s)
                    \\
                    \\Vậy tốc độ thay đổi của z khi x=2 cm  và y=3 cm là 15 ($cm^2$/s)

                    


           
           
           
            
        \end{enumerate}
        
        
        
        

       

        
\end{document}
