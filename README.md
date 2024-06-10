# SEO Latest Posts

### This project is to create BOT that fetch latest news from site map of list of website, store to DB and send to user.

## Input:

- List of site map to crawl. It may support different format:

    - xml: https://fptshop.com.vn/News-1.xml
    - rss: https://fptshop.com.vn/thu-thuat.rss

- 

## Output

- With rss:
    - Get item title.
    - Get item link.
    - Get publish date.

## Example data

RSS:

```xml
<channel>
    <lastBuildDate>Mon, 10 Jun 2024 22:00:02 +0700</lastBuildDate>
    <title>FPTShop - Tin Tức</title>
    <description>FPTShop - Thủ Thuật</description>
    <link>https://fptshop.com.vn/tin-tuc/thu-thuat</link>
    <item>
        <guid isPermaLink="false">an-noi-dung-thong-bao-tren-man-hinh-khoa-xiaomi-187404</guid>
        <pubDate>Mon, 10 Jun 2024 19:54:38 +0700</pubDate>
        <title>Ẩn nội dung thông báo trên Màn hình khóa Xiaomi qua 7 cách đơn giản, dễ dàng thực hiện</title>
        <description>Ẩn nội dung thông báo trên Màn hình khóa Xiaomi là một trong những vấn đề được người dùng điện thoại Xiaomi tìm kiếm cách khắc phục nhiều nhất. Để giúp bạn giải quyết vấn đề này, FPT Shop xin gửi đến bạn ba cách chính để bạn có thể ẩn đi những thông báo phiền nhiễu trên Màn hình khóa Xiaomi của bạn!</description>
        <link>https://fptshop.com.vn/tin-tuc/thu-thuat/an-noi-dung-thong-bao-tren-man-hinh-khoa-xiaomi-187404</link>
        <author>hhoanglong373@gmail.com (CTV)</author>
    </item>
</channel>
```
