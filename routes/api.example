<?php

use App\Http\Controllers\v1\CargoControllers;
use Illuminate\Http\Request;
use Illuminate\Support\Facades\Route;

/*
|--------------------------------------------------------------------------
| API Routes
|--------------------------------------------------------------------------
|
| Here is where you can register API routes for your application. These
| routes are loaded by the RouteServiceProvider within a group which
| is assigned the "api" middleware group. Enjoy building your API!
|
*/

Route::middleware('auth:sanctum')->get('/user', function (Request $request) {
    return $request->user();
});

Route::get("/cargo",[CargoControllers::class,"obtenerLista"]);
Route::get("/cargo/{id}",[CargoControllers::class,"obtenerItem"]);
Route::post("/cargo",[CargoControllers::class,"create"]);
Route::put("/cargo",[CargoControllers::class,"update"]);
Route::patch("/cargo",[CargoControllers::class,"patch"]);
Route::delete("/cargo/{id}",[CargoControllers::class,"delete"]);