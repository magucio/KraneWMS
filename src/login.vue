<template>
<html>
<head>
  <!-- ... -->
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="tailwind.css" rel="stylesheet">
</head>
<body>

<!--login page-->

<div class="flex items-center justify-center min-h-screen bg-gray-900">

    <div class="px-8 py-6 mt-4 text-left bg-gray-800 shadow-lg rounded px-8 pt-6 pb-8 mb-4">
        <div class="flex justify-center">
            <svg class="h-24 w-24 fill-current text-purple-600" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                <path d="M11 17a1 1 0 001.447.894l4-2A1 1 0 0017 15V9.236a1 1 0 00-1.447-.894l-4 2a1 1 0 00-.553.894V17zM15.211 6.276a1 1 0 000-1.788l-4.764-2.382a1 1 0 00-.894 0L4.789 4.488a1 1 0 000 1.788l4.764 2.382a1 1 0 00.894 0l4.764-2.382zM4.447 8.342A1 1 0 003 9.236V15a1 1 0 00.553.894l4 2A1 1 0 009 17v-5.764a1 1 0 00-.553-.894l-4-2z" />
              </svg>
        </div>
        <div class="">
            <h3 class="text-2xl font-bold text-center fill-current text-gray-200 font-bold">Krane WMS</h3>
        </div>
        <div class="w-full max-w-xs">
            <form class="space-y-4">
                <div class="mb-4">
                    <label class="block text-gray-500 text-sm font-bold mb-2" for="login">
                        Login
                    </label>
                    <input class="bg-gray-600 appearance-none border-2 border-gray-400 rounded w-full py-2 px-4 text-gray-400 leading-tight focus:outline-none focus:bg-gray-700 focus:border-purple-500" id="login" type="text" placeholder="Your login">
                </div>
                <div class="mb-6">
                    <label class="block text-gray-500 text-sm font-bold mb-2" for="password">
                      Password
                    </label>
                    <input class="bg-gray-600 appearance-none border-2 border-gray-400 rounded w-full py-2 px-4 text-gray-400 leading-tight focus:outline-none focus:bg-gray-700 focus:border-purple-500" id="password" type="password" placeholder="Your password">
                </div>
                <div class="flex items-center justify-between">
                    <button class="bg-purple-600 hover:bg-purple-900 text-gray-200 font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
                      Sign In
                    </button>
                    <a class="inline-block align-baseline font-bold text-sm text-gray-500 hover:text-purple-200" href="#">
                      Forgot Password?
                    </a>
                </div>
            </form>            
        </div>
</div>

</body>
</html>
</template>
