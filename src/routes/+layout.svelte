<html lang="html" data-theme="light">
    <nav>
        <div class="container">
            <nav class="container-fluid">
                <ul>
                    <li>
                        <a href="/" class="test"><img class="logo" src="data:image/svg+xml;charset=utf-8;base64,PHN2ZyB3aWR0aD0iNDI4IiBoZWlnaHQ9IjUwMCIgdmlld0JveD0iMCAwIDQyOCA1MDAiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxwYXRoIGQ9Ik0wIDI1MEg3Ny43MkwxNTUuNDMgNDE2LjY3TDM0OS43MyAwSDQyNy40NUwxOTQuMjkgNTAwSDExNi41OEwwIDI1MFoiIGZpbGw9IiNFRTAwMDAiLz4KPC9zdmc+Cg==" alt=""></a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a class="text-white" href="/credits">Credits</a>
                    </li>
                    <li>
                        <a class="text-white" target="_blank" href="https://github.com/hhhtylerw/gatorhacks-2023">GitHub</a>
                    </li>
                </ul>
        
            </nav>
        </div>
    </nav>

</html>


<slot />

<style>
    .text-white {
        color: white;
        font-size: 16px;
        font-weight: bold;
        font-family: Palanquin, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    }
    .logo {
        max-width: 30px;
    }
    nav {
		background-color: black;
		box-shadow: var(--card-box-shadow);
	}
</style>