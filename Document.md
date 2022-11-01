Sass:

- Base on Ruby
- Có 2 phiên bản là: SCSS & SASS
- SCSS: sử dụng nhiều, cú pháp giống như CSS

\*Sass Concept

1. Variable:

- Dat ten bien:
  $maintextColor: orange;
  Note: Tach tat ca cac bien cua project vao 1 file

2.  Nested
    nav{
    ul{
    margin: 0px;
    padding: 0px;
    list-style-type: none;
    li{
    display: inline-block;
    a{
    display: block;
    text-decoration: none;
    color: $textColor;
    font-size: $normalSize;
    padding: 15px;
    background: $linkBgColor;
    &:hover{
    background: $linkBgHover;
    color: $textLinkColorHover;
    }
    }
    }
    }
    }

3.  Mixin

- Cu phap:
  @mixin mixinName{
  css attribute1
  css attribute2
  css attribute3
  css attribute4
  }
- Su dung mixin:
  @inlucde ten_mixin

4. Extent

- Cu phap:
  Ke thua 1 class co san
  .register{
  color: #fff;
  background: orange;
  font-size: 1.1rem;
  border: none;
  border-radius: 5px;
  padding: 10px;
  }
  .border{
  border: 1px solid red;
  }
  .content{
  @extend.register;
  @extend.border;
  margin-top: 10px;
  max-width: 500px;
  }

  5.If Else

6. Loop (for, foreach)
