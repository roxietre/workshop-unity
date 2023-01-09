
## Step 0:

Please refer to the [SETUP.md](./SETUP.md) file.

## Step 1 -object creation:

### 📑 **Description**:

In this step you will learn how to create and scale object. 

### 📌 **Tasks**:

    - Create two 3D object 
        -name the first one "player"
        -and the other "floor"
    - give as paramater for "floor" scale : x:10 , y:10

<details> 
<summary>✔️ Result preview</summary>
<img src="https://imgs.search.brave.com/vdp1RxIcnfOppr-tGB1V4MzKOZtHaJzEJX9qsxpEJKQ/rs:fit:1200:720:1/g:ce/aHR0cHM6Ly9pLnl0/aW1nLmNvbS92aS9f/T0dnNjkwSV9WWS9t/YXhyZXNkZWZhdWx0/LmpwZw" alt="backround image"/>
</details>

## Step 2 -color of objets:

### 📑 **Description**:

In this step you will learn how to create material object and apply it on a 3D object.

### 📌 **Tasks**:

    - Create a Material object
        -chose your material
        -chose your color
    - slide the Material on your "player" object
    - do the same but this time for the "floor" object 

<details> 
<summary>✔️ Result preview</summary>
<img src="https://imgs.search.brave.com/i95UR2xT-8DaAgmu5WDPvkhjMrl4QT6Lhf3h3_3c-NQ/rs:fit:1200:1200:1/g:ce/aHR0cHM6Ly9jb25u/ZWN0LXByZC1jZG4u/dW5pdHkuY29tLzIw/MTkxMjA0L2xlYXJu/L2ltYWdlcy8yNzc2/ZjE5My0yMzkyLTRl/NjYtYjkzMi03OTg0/MmZmNWRmNjNfYWxi/ZWRvLnBuZw" alt="backround image">
</details>

## Step 3 -body:

### 📑 **Description**:

In this step you will learn how to add a body to an 3D object.
Rigidbody in Unity allows your GameObjects to act under the control of physics.

### 📌 **Tasks**:

    - add a RigidBody component to your "player" object (you gonna find it in the Add Componet menu)

<details> 
<summary>✔️ Result preview</summary>
<img src="https://answers.unity.com/storage/temp/166955-poznamka-2020-09-05-123240.png" alt="backround image">
</details>

## Step 4 -first script

### 📑 **Description**:

Script in unity are one if the main fiture its allow you to affect code to a object.
in this step you will learn how to link a script with a object and add value to this object

### 📌 **Tasks**:

    - add a new component script to your "player" object name it "Mouvement"
    - now double click the on script to open it
    - in the class named "Mouvement" add 2 private float one for the "speedForce" and "jumpForce"

<details>   
<summary>✔️ Result preview</summary>
<img src="https://docs.unity3d.com/510/Documentation/uploads/Main/AnalyticsMainCameraComponent.png" alt="backround image">
</details>

## Step 5 - player mouvement

### 📑 **Description**:

In this task you gonna learn how to move a object using script previusly add to this object and also manage input.
In unity to manage input they using a [keyCode](https://docs.unity3d.com/ScriptReference/KeyCode.html) its a class where you can find every keyboard key.

```c#
KeyCode.X //for a x key 
KeyCode.T //for a t key
```

In unity all the input that a player can make are store in th [Input](https://docs.unity3d.com/ScriptReference/Input.html) class im sure your gonna find whats you looking for there

```c#
if (Input.GetMouseButton(0))
{
    Debug.Log("Pressed left click.");
}

```

### 📌 **Tasks**:

    - make the "player" object move when Z,Q,S,D key are press
        - use "speedForce" to make a smouth mouvement
    - make the "player" object jump when space key is press
        -  use "jumpForce" to make a smouth jump


<details> 
<summary>✔️ Result preview</summary>
<img src="https://imgs.search.brave.com/2y2GvJ-vWhdzDNvtUCfOSac-ZY2iyAFrK63Vs7t8V98/rs:fit:766:435:1/g:ce/aHR0cHM6Ly9tZWRp/YS5naXBoeS5jb20v/bWVkaWEvdVNEaVNC/RlJOVVplVS9naXBo/eS5naWY.gif" alt="backround image">
</details>

