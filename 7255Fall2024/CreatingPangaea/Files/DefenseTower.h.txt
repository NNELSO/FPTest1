// Fill out your copyright notice in the Description page of Project Settings.

#pragma once

#include "CoreMinimal.h"
#include "GameFramework/Actor.h"
#include "DefenseTower.generated.h"

UCLASS()
class PANGAEA_API ADefenseTower : public AActor
{
	GENERATED_BODY()

public:
	// Sets default values for this actor's properties
	ADefenseTower();

	int HealthPoints = 100; //Starting default values(health)
	int ShellDenfense = 2; 
	float AttackRange = 15.0f; //default attack range the f at the end if 15 is paired with the float not a measurement
	float ReloadInterval = 1.0f;

protected:
	// Called when the game starts or when spawned
	virtual void BeginPlay() override;

	int _HealthPoints; //tower's current health points
	float _ReloadCountingDown; 

public:
	// Called every frame
	virtual void Tick(float DeltaTime) override;

	int GetHealthPoints(); 
	bool IsDestroyed(); //the bool indacates a yes or no, true or false.
	bool CanFire();
	void Fire();
	void Hit(int damage);

protected:
	void DestroyProcess();
};
