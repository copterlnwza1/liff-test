<!DOCTYPE html> 
<html> 
<head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0,viewport-fit=cover">
<title>LIFF - LINE Front-end Framework</title> 
</head> 
<body>
  <script src="https://static.line-scdn.net/liff/edge/versions/2.5.0/sdk.js"></script>
  <script> 
      async function main() {
await liff.init({ liffid: "1656955999-BQ48GxYa" }) 
await liff. share TargetPicker([
    type: "flex",
    altText: "Flex Message from Share Target Picker", 
    contents: {
    "messages":[
{
  "type": "flex",
  "altText": "โอนให้แล้วนะ 50.- ",
  "contents": {
  "type": "bubble",
  "size": "giga",
  "hero": {
    "type": "image",
    "url": "https://sv1.picz.in.th/images/2022/03/07/rsWsNn.jpg",
    "size": "full",
    "aspectRatio": "1:1",
    "aspectMode": "cover",
    "action": {
      "type": "uri",
      "uri": "https://lin.ee/APJg1NR"
    },
    "margin": "none"
  },
  "footer": {
    "type": "box",
    "layout": "vertical",
    "spacing": "md",
    "contents": [
      {
        "type": "button",
        "style": "primary",
        "height": "md",
        "action": {
          "type": "uri",
          "label": "รับเครดิตฟรี",
          "uri": "https://lin.ee/APJg1NR"
        },
        "color": "#dc3545",
        "margin": "sm",
        "gravity": "center",
        "offsetBottom": "none"
      },
      {
        "type": "button",
        "action": {
          "type": "uri",
          "label": "ส่งให้เพื่อน",
          "uri": "https://social-plugins.line.me/lineit/share?url=https://lin.ee/APJg1NR"
        },
        "color": "#dc3545",
        "style": "primary"
      },
      {
        "type": "spacer",  
        "size": "md"
      }
    ],
    "flex": 0,
    "margin": "none"
  },
  "styles": {
    "footer": {
      "separator": true 
    }
  }
}
}
    ]
}
}
    ])
    liff.closeWindow()
    }
main() 
</scripti>
</body> 
</html>
