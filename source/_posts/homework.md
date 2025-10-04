---
title: homework
date: 2025-10-04 14:16:15
tags:
---
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>米哈游游戏官网</title>
    <!-- 引入Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- 引入Font Awesome -->
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    
    <!-- 配置Tailwind自定义颜色和字体 -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        genshin: '#7B61FF',
                        zenless: '#FF4D4F',
                        starrail: '#00A3FF',
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    
    <style type="text/tailwindcss">
        @layer utilities {
            .link-card {
                @apply bg-white rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-xl hover:-translate-y-1;
            }
            .link-image {
                @apply w-full h-48 object-cover transition-transform duration-500 hover:scale-105;
            }
            .link-title {
                @apply text-xl font-bold text-gray-800 mb-2;
            }
            .link-description {
                @apply text-gray-600 mb-4;
            }
        }
    </style>
</head>
<body class="bg-gray-100 min-h-screen">
    <div class="container mx-auto px-4 py-12">
        <header class="text-center mb-12">
            <h1 class="text-4xl font-bold text-gray-800 mb-4">米哈游游戏官网</h1>
            <p class="text-gray-600 max-w-2xl mx-auto">以下是米哈游旗下热门游戏的官方网站链接，点击图片或卡片即可访问。</p>
        </header>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- 原神官网链接 -->
            <a href="https://genshin.hoyoverse.com/" target="_blank" class="link-card group">
                <div class="overflow-hidden">
                    <img src="https://picsum.photos/id/1035/600/400" alt="原神游戏场景，展示了奇幻的开放世界景观" class="link-image">
                </div>
                <div class="p-6">
                    <div class="flex items-center mb-3 text-genshin">
                        <i class="fa fa-gamepad mr-2 text-xl"></i>
                        <span class="font-medium">开放世界</span>
                    </div>
                    <h2 class="link-title group-hover:text-genshin transition-colors">原神</h2>
                    <p class="link-description">探索奇幻大陆提瓦特，与众多角色一同踏上寻找失散亲人的冒险之旅。</p>
                    <div class="text-genshin font-medium flex items-center">
                        访问官网 <i class="fa fa-external-link ml-2 transition-transform group-hover:translate-x-1"></i>
                    </div>
                </div>
            </a>
            
            <!-- 绝区零官网链接 -->
            <a href="https://zenless.hoyoverse.com/" target="_blank" class="link-card group">
                <div class="overflow-hidden">
                    <img src="https://picsum.photos/id/160/600/400" alt="绝区零游戏风格图片，展示了都市战斗场景" class="link-image">
                </div>
                <div class="p-6">
                    <div class="flex items-center mb-3 text-zenless">
                        <i class="fa fa-bolt mr-2 text-xl"></i>
                        <span class="font-medium">都市动作</span>
                    </div>
                    <h2 class="link-title group-hover:text-zenless transition-colors">绝区零</h2>
                    <p class="link-description">在新艾利都的危险"空洞"中展开激烈战斗，体验快节奏的动作游戏乐趣。</p>
                    <div class="text-zenless font-medium flex items-center">
                        访问官网 <i class="fa fa-external-link ml-2 transition-transform group-hover:translate-x-1"></i>
                    </div>
                </div>
            </a>
            
            <!-- 崩坏：星穹铁道官网链接 -->
            <a href="https://hsr.hoyoverse.com/" target="_blank" class="link-card group">
                <div class="overflow-hidden">
                    <img src="https://picsum.photos/id/110/600/400" alt="星穹铁道游戏场景，展示了星际列车和宇宙景观" class="link-image">
                </div>
                <div class="p-6">
                    <div class="flex items-center mb-3 text-starrail">
                        <i class="fa fa-rocket mr-2 text-xl"></i>
                        <span class="font-medium">回合制RPG</span>
                    </div>
                    <h2 class="link-title group-hover:text-starrail transition-colors">崩坏：星穹铁道</h2>
                    <p class="link-description">登上星穹列车，穿梭于不同星球之间，展开一段跨越银河的奇妙冒险。</p>
                    <div class="text-starrail font-medium flex items-center">
                        访问官网 <i class="fa fa-external-link ml-2 transition-transform group-hover:translate-x-1"></i>
                    </div>
                </div>
            </a>
        </div>
        
        <footer class="mt-16 text-center text-gray-500">
            <p>© 2023 米哈游游戏官网导航 | 点击任意卡片访问对应游戏官网</p>
        </footer>
    </div>
</body>
</html>

