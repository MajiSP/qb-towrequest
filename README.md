# **A simple tow request script using qb-target | renewed qb-phone**

## **qb-target:**

### https://github.com/qbcore-framework/qb-target

## **Renewed QB-Phone:**

### https://github.com/Renewed-Scripts/qb-phone



# **INSTALLATION**



## *PLACE THIS INSIDE YOUR qb-target/init.lua >*
```
Config.TargetBones = {
	["requestTow"] = {
        bones = {
            "seat_dside_f",
        },
        options = {
            {
                type = "client",
                event = "tow:requestTow",
                icon = "fas fa-truck",
                label = "Request Tow",
            },
        },
        distance = 4.0
    },
}
```

Make sure your qb-core/shared/jobs.lua has a job named "tow". 
======================================- 

That's it. Just ensure it inside your server.cfg and play!