<nav class="w-[90vw] max-w-[1000px] h-18 py-4 px-4 flex flex-row gap-4 justify-between items-center fixed top-4 left-1/2 -translate-x-1/2 bg-black rounded-xl">
      <div class="h-full flex flex-col justify-center px-8 w-48 -space-y-1">
            <a href="./#" class="w-fit text-2xl font-bold">KPRS</a>
      </div>
      <div class="w-full flex justify-center">
            <div class="flex flex-row gap-6 *:duration-200">
                  <a class="navbar-link" href="#about">About</a>
                  <a class="navbar-link" href="#tutorial">Tutorial</a>
            </div>
      </div>
      <button class="h-full bg-white text-black rounded-xl px-6 text-xl font-semibold border border-transparent cursor-pointer duration-150 hover:bg-transparent hover:border-white hover:text-white">
            Vote
      </button>
</nav>

<style>
      a.navbar-link {
            position: relative;
      }
      
      a.navbar-link::after {
            content: "";
            display: block;
            width: 0;
            position: absolute;
            bottom: -4px;
            height: 1px;
            background-color: white;
            transition-duration: 300ms;
            right: 0;
      }

      a.navbar-link:hover::after { 
            width: 100%;
            left: 0;
      }
</style>