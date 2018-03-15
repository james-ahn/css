# css
studying for css

## making img bigger by animation
```
      img:hover{ /* img 마우스 오버시*/
        cursor:pointer;
        transform:scale(1.5); /* 마우스 오버시 이미지 크기를 1.1 배만큼 확대시킨다. */
        -o-transform:scale(1.5);
        -moz-transform:scale(1.5);
        -webkit-transform:scale(1.5);

        transition: transform .35s;
        -o-transition: transform .35s;
        -moz-transition: transform .35s;
        -webkit-transition: transform .35s;
        /* 마우스 오버시 이미지가 즉시 커지지않고 30.5 second 의 시간에 걸쳐 커진다 애니메이션 효과*/
      }
      
```
