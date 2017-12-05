# css-bgImgAutoFit

* {
                margin: 0;
                padding: 0;
            }

            .kech {
                background-image: url(img/video-img.jpg);
                background-size: 100% auto;
                background-repeat: no-repeat;
                width: 100%;
            }

            .kech:before {
                content: "";
                display: block;
                padding-top: 60%; // 图片真实高度/宽度 * 100
            }

            .kech1 img {
                width: 100%;
            }
