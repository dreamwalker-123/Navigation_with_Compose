Jetpack Compose Navigation practice

what do we have here:
1) val navController: NavHostController = rememberNavController()
2) val backStackEntry by navController.currentBackStackEntryAsState()
3) NavHost() { composable("screen_1") }
4) navController.navigate("screen_1")
