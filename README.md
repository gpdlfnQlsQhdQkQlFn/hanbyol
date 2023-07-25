<!--@layout(/layout/basic/layout.html)-->
<!--@js(/layout/basic/js/main.js)-->
<!--@css(/layout/basic/css/main.css)-->

        
</div>
<!DOCTYPE html>
<html>
<head>
    <title>와인 구독 서비스</title>
    <style>
      header {
            background-color: #FECCBE;
            padding: 30px;
            text-align: center;
        }  
        main {
            padding: 70px;
            text-align: center;
        }
        footer {
            background-color: #EEEEEE;
            padding: 5px;
            text-align: center;
        }
         p {
            font-size: 20px; /* 원하는 크기로 조정하세요 */
             padding: 5px;
            text-align: center;
        }
         
    </style>
</head>
<body>
    

    <main> 
        <h1>와인 구독 서비스란?</h1>
       
        <p>선결제 시스템과 유사합니다. 원하는 금액을 결제한 후 원하는 서비스를 선택합니다.</p>
        </div> </main>
    <header>
        <p>1. 내가 원하는 스타일의 와인 or 추천와인을 원하는 수량만큼 매월 정기적으로 택배 수령</p>
        <p>2. 내가 원할 때 전화 및 카톡요청을 통해 그때그때 와인 수령</p>
          </header> 
    	
<main>
    		<p>* 컨시어즈는 잔액 소진과 동시에 종료됩니다.</p>
    
    <p>* 와인 차감이 이루어질 시에는 소진되는 와인명과 금액, 잔액에 관한 영수증을 전달드립니다.</p>
    <p>* 계산서 혹은 현금영수증도 발행가능합니다.</p>
    </main>
     <!-- 이미지 삽입 -->
        <img src="/web/upload/category/editor/2023/07/21/ef1adeac3cf90348fdef7684edbd9919.png"  alt="와인 이미지"style="display: block; margin: 0 auto;">
        <!-- 나머지 내용 생략 -->

    <footer>
        <p> 주) 이뱅와인/이뱅월드</p>
                <p> 우리은행 1005 003 284400 이뱅월드</p>

    </footer>
</body>
</html>

<body>
   

<div module="product_listrecommend" class="ec-base-product">
    <!--
        $count = 4
            ※ 상품진열갯수를 설정하는 변수입니다. 설정하지 않을 경우, 최대 200개의 상품이 진열 됩니다.
            ※ 진열된 상품이 많으면, 쇼핑몰에 부하가 발생할 수 있습니다.
        $basket_result = /product/add_basket.html
        $basket_option = /product/basket_option.html
    -->
    <div class="title">
        <h3><span>BEST SELLERS</span></h3>
    </div>
    <ul class="prdList grid4">
        <li id="anchorBoxId_{$product_no}">
            <span class="chk"><input type="checkbox" class="{$product_compare_class} {$product_compare_display|display}" /></span>
            <div class="thumbnail">
                <a href="/product/detail.html{$param}" name="anchorBoxName_{$product_no}"><img src="{$image_medium}" id="{$image_medium_id}" alt="{$seo_alt_tag}" /><span module="product_Imagestyle"><span class="prdIcon {$icon_class_name}" style="background-image:url('{$icon_url}');"></span></span></a>
                <span class="wish">{$list_wish_icon}</span>
            </div>
            <div class="description">
                <div class="icon">
                    <div class="promotion">{$soldout_icon} {$stock_icon} {$recommend_icon} {$new_icon} {$product_icons} {$benefit_icons}</div>
                    <div class="button"><div class="option">{$option_preview_icon}</div> {$basket_icon} {$zoom_icon}</div>
                </div>
                <strong class="name"><a href="/product/detail.html{$param}" class="{$product_name_display|display}"><span class="title {$product_name_title_display|display}">{$product_name_title} :</span> {$product_name}</a></strong>
                <ul module="product_ListItem" class="spec">
                    <li class="{$item_display|display}"><strong class="title {$item_title_display|display}">{$item_title} :</strong> {$item_content}</li>
                    <li class="{$item_display|display}"><strong class="title {$item_title_display|display}">{$item_title} :</strong> {$item_content}</li>
                </ul>
            </div>
        </li>
        <li id="anchorBoxId_{$product_no}">
            <span class="chk"><input type="checkbox" class="{$product_compare_class} {$product_compare_display|display}" /></span>
            <div class="thumbnail">
                <a href="/product/detail.html{$param}" name="anchorBoxName_{$product_no}"><img src="{$image_medium}" id="{$image_medium_id}" alt="{$seo_alt_tag}" /><span module="product_Imagestyle"><span class="prdIcon {$icon_class_name}" style="background-image:url('{$icon_url}');"></span></span></a>
                <span class="wish">{$list_wish_icon}</span>
            </div>
            <div class="description">
                <div class="icon">
                    <div class="promotion">{$soldout_icon} {$stock_icon} {$recommend_icon} {$new_icon} {$product_icons} {$benefit_icons}</div>
                    <div class="button"><div class="option">{$option_preview_icon}</div> {$basket_icon} {$zoom_icon}</div>
                </div>
                <strong class="name"><a href="/product/detail.html{$param}" class="{$product_name_display|display}"><span class="title {$product_name_title_display|display}">{$product_name_title} :</span> {$product_name}</a></strong>
                <ul module="product_ListItem" class="spec">
                    <li class="{$item_display|display}"><strong class="title {$item_title_display|display}">{$item_title} :</strong> {$item_content}</li>
                    <li class="{$item_display|display}"><strong class="title {$item_title_display|display}">{$item_title} :</strong> {$item_content}</li>
                    
                </ul>
            </div>
        </li>
    </ul>
</div>
</div>
</div>
</div>
</div>
<div module="product_listnew" class="ec-base-product">
    <!--
        $count = 5
            ※ 상품진열갯수를 설정하는 변수입니다. 설정하지 않을 경우, 최대 200개의 상품이 진열 됩니다.
            ※ 진열된 상품이 많으면, 쇼핑몰에 부하가 발생할 수 있습니다.
        $basket_result = /product/add_basket.html
        $basket_option = /product/basket_option.html
    -->
    <div class="title">
        <h3><span>NEW ARRIVALS</span></h3>
    </div>
    <ul class="prdList grid5">
        <li id="anchorBoxId_{$product_no}">
            <span class="chk"><input type="checkbox" class="{$product_compare_class} {$product_compare_display|display}" /></span>
            <div class="thumbnail">
                <a href="/product/detail.html{$param}" name="anchorBoxName_{$product_no}"><img src="{$image_medium}" id="{$image_medium_id}" alt="{$seo_alt_tag}" /><span module="product_Imagestyle"><span class="prdIcon {$icon_class_name}" style="background-image:url('{$icon_url}');"></span></span></a>
                <span class="wish">{$list_wish_icon}</span>
            </div>
            <div class="description">
                <div class="icon">
                    <div class="promotion">{$soldout_icon} {$stock_icon} {$recommend_icon} {$new_icon} {$product_icons} {$benefit_icons}</div>
                    <div class="button"><div class="option">{$option_preview_icon}</div> {$basket_icon} {$zoom_icon}</div>
                </div>
                <strong class="name"><a href="/product/detail.html{$param}" class="{$product_name_display|display}"><span class="title {$product_name_title_display|display}">{$product_name_title} :</span> {$product_name}</a></strong>
                <ul module="product_ListItem" class="spec">
                    <li class="{$item_display|display}"><strong class="title {$item_title_display|display}">{$item_title} :</strong> {$item_content}</li>
                    <li class="{$item_display|display}"><strong class="title {$item_title_display|display}">{$item_title} :</strong> {$item_content}</li>
                </ul>
            </div>
        </li>
        <li id="anchorBoxId_{$product_no}">
            <span class="chk"><input type="checkbox" class="{$product_compare_class} {$product_compare_display|display}" /></span>
            <div class="thumbnail">
                <a href="/product/detail.html{$param}" name="anchorBoxName_{$product_no}"><img src="{$image_medium}" id="{$image_medium_id}" alt="{$seo_alt_tag}" /><span module="product_Imagestyle"><span class="prdIcon {$icon_class_name}" style="background-image:url('{$icon_url}');"></span></span></a>
                <span class="wish">{$list_wish_icon}</span>
            </div>
            <div class="description">
                <div class="icon">
                    <div class="promotion">{$soldout_icon} {$stock_icon} {$recommend_icon} {$new_icon} {$product_icons} {$benefit_icons}</div>
                    <div class="button"><div class="option">{$option_preview_icon}</div> {$basket_icon} {$zoom_icon}</div>
                </div>
                <strong class="name"><a href="/product/detail.html{$param}" class="{$product_name_display|display}"><span class="title {$product_name_title_display|display}">{$product_name_title} :</span> {$product_name}</a></strong>
                <ul module="product_ListItem" class="spec">
                    <li class="{$item_display|display}"><strong class="title {$item_title_display|display}">{$item_title} :</strong> {$item_content}</li>
                    <li class="{$item_display|display}"><strong class="title {$item_title_display|display}">{$item_title} :</strong> {$item_content}</li>
                </ul>
            </div>
        </li>
        
    </ul>
</div>



<div module="product_normalpaging" class="ec-base-paginate">
    <a href="{$param_first}" class="first"><img src="https://img.echosting.cafe24.com/skin/base/common/btn_page_first.gif" alt="첫 페이지" /></a>
    <a href="{$param_before}"><img src="https://img.echosting.cafe24.com/skin/base/common/btn_page_prev.gif" alt="이전 페이지" /></a>
    <ol>
        <li><a href="{$param}" class="{$param_class}">{$no}</a></li>
        <li><a href="{$param}" class="{$param_class}">{$no}</a></li>
        <li><a href="{$param}" class="{$param_class}">{$no}</a></li>
        <li><a href="{$param}" class="{$param_class}">{$no}</a></li>
        <li><a href="{$param}" class="{$param_class}">{$no}</a></li>
    </ol>
    <a href="{$param_next}"><img src="https://img.echosting.cafe24.com/skin/base/common/btn_page_next.gif" alt="다음 페이지" /></a>
    <a href="{$param_last}" class="last"><img src="https://img.echosting.cafe24.com/skin/base/common/btn_page_last.gif" alt="마지막 페이지" /></a>
</div>

<!-- 공급사:판매사정보 -->
<div module="Mall_SupplyInfo" class="supplyInfo {$supply_info_display|display}">
    {$supply_info}
</div>
<!-- //공급사:판매사정보 -->

<!--@define(cmc_log)-->



