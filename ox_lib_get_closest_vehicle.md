Shared
lib.getClosestVehicle
Get the vehicle handle and coords of the closest vehicle to a set of coordinates.

lib.getClosestVehicle(coords, maxDistance, includePlayerVehicle)
coords: vector3
The coords to check from.
maxDistance?: number
The max distance to check.
Default: 2.0
includePlayerVehicle?: boolean
Whether or not to include the player's current vehicle. Ignored on the server.
Default: false
Return:

vehicle?: number
vehicleCoords?: vector3
