#   pencq��R 
  
  
 # #   MR ��V u e   N!jg 
  
 O(uek��:  
  
 1 .   �Q  u�b�  * * !jg* *    
       1 .   �v�c(W  H T M L   h~{-N�Q  h~{ 
       2 .   O(u  t e m p l a t e  
       3 .   O(u  US�e�N  (   < t e m p l a t e   / >   )  
 2 .   R�^  * * V u e   �[�O* *  
       -   (W  V u e   �v�g ��Qpe-N�c�O:   d a t a ,   m e t h o d s ,   c o m p u t e d ,   w a t c h e r ,   p r o p s ,   . . .  
 3 .   \  V u e   * * c}�* * 0R  u�b�-N  (   m o u n t   )  
  
 ` ` ` j s  
 l e t   a p p   =   n e w   V u e ( {  
         e l :   " # r o o t " ,  
         d a t a :   {  
                 m e s s a g e :   " l i u " ,  
         } ,  
 } ) ;  
 / / v u e j s OꁨR�v\vQc}�0Ru�b�-N 
 ` ` `  
  
  
  
 # #   pencq��R!j�W 
  
 V u e   �vgbL�Amz 
  
 1 .   ���_!jg:   !jg-N	g  " QW"  
 2 .   )R(u  V u e   �g ��Qpe-N@b�c�O�vpenceg  " kXQW" ,   �_0R�S�N(Wu�b�-N>f:y�v  " h~{"  
 3 .   \h~{�fbcu�b�-N�Seg	gQW�vh~{ 
  
 ;`�veg��V u e   )R(u  b�N�c�O�vpenc  �T  u�b�-N  !jg  ub�N   N*N�e�v  H T M L   h~{  (   n o d e   CQ }  ) , �fbc0R�N  u�b�-N  >en!jg�vMOn.  
  
  
  
 wQSO�[�s� 
  
 1 .   �b0R!jg 
  
 2 .   �b0Rpenc  (   d a t a   )  
 3 .   \pencN!jg�~T,   �_0R  �v/f  H T M L   CQ }  (   D O M   CQ }  )  
 4 .   >e0Ru�b�-N 
  
 ` ` ` j s  
 < s c r i p t >  
         / /   (u�N�fbc�vckRh���_ĉR 
         l e t   r e g E x p   =   / \ { \ { ( . + ? ) \ } \ } / g ;  
 / /   1 . �b0R!jg� 
 l e t   t e m p l a t e   =   d o c u m e n t . q u e r y S e l e c t o r ( " # r o o t " ) ;  
 / /   2 . �b0Rpenc� 
 l e t   d a t a   =   {  
         n a m e :   " l i u " ,  
         a g e :   2 1 ,  
 } ;  
 / /   3 . \penc�T!jg�~T��_0R N*N�e�vD O M CQ }� 
 f u n c t i o n   c o m p i l e r ( n o d e ,   d a t a )   {  
         / /   3 . 1 ���S@b	gP[���p 
         l e t   c h i l d N o d e s   =   n o d e . c h i l d N o d e s ;  
         f o r   ( v a r   i   =   0 ;   i   <   c h i l d N o d e s . l e n g t h ;   i + + )   {  
                 l e t   t y p e   =   c h i l d N o d e s [ i ] . n o d e T y p e ;  
                 i f   ( t y p e   = =   3 )   {  
                         / /   3 . 2 �e,g���pMb�^(uckRh���_ۏL��fbc 
                         v a r   t e x t   =   c h i l d N o d e s [ i ] . n o d e V a l u e . r e p l a c e ( r e g E x p ,   f u n c t i o n   ( m a t c h , $ 1 )   {  
                                 r e t u r n   d a t a [ $ 1 . t r i m ( ) ] ; / / t r i m ( ) �v\O(u/fnd��c!jgW[&{MRT�vzz<h��k�Y{ {       n a m e       } }  
                         } ) ;  
                         / /   3 . 2 . 1 \勇e,g���p�v�Q�[͑�e��n:N g�e�fbc�v�Q�[ 
                         c h i l d N o d e s [ i ] . n o d e V a l u e   =   t e x t ;  
                 }   e l s e   i f   ( t y p e   = =   1 )   {  
                         / /   3 . 3 �[�NCQ }���p� ���ۏL��R_ 
                         c o m p i l e r ( c h i l d N o d e s [ i ] ,   d a t a ) ;  
                 }  
         }  
 }  
 / /   4 . :N�NN9e�S�Seg�v!jg� ���KQ���Q N*N�e�vd o m CQ }� 
 v a r   g e n e r a t e N o d e   =   t e m p l a t e . c l o n e N o d e ( t r u e ) ;  
 c o m p i l e r ( g e n e r a t e N o d e ,   d a t a ) ;  
 / /   5 . \�e�vD O M CQ }�fbc�c�Seg�vd o m CQ }� 
 t e m p l a t e . p a r e n t N o d e . r e p l a c e C h i l d ( g e n e r a t e N o d e ,   t e m p l a t e ) ;  
 c o n s o l e . l o g ( r o o t ) ;  
 < / s c r i p t >  
 ` ` `  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
 #   �{US�v!jg2n�g 
  
  
  
 #   Z��b  D O M  
  
 �vh:  
  
 1 .   `HN\wck�v  D O M   l�bc:N  Z��b  D O M  
 2 .   `HN\Z��b  D O M   l�bc:N  wck�v  D O M  
  
 `�N�m�b�{|<O 
  
  
  
  
  
 