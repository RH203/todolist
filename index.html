<?php include 'config.php'; ?>

<?php 

    if(isset($_POST['add_post'])){
        $task_name = mysqli_real_escape_string($connection,$_POST['task_name']);
        $query = mysqli_query($connection,"INSERT INTO task (task_name, task_status, task_date) 
                                            VALUE ('$task_name','pending',now()) ");
        header("Location: index.php");
    }

    if(isset($_GET['edit'])){
        $task_id = $_GET['edit'];
        $query = mysqli_query($connection, "UPDATE task SET task_status='DONE' WHERE task_id='$task_id' ");
        header("Location: index.php");
    }

    if(isset($_GET['delete'])){
      $task_id = $_GET['delete'];
      $query = mysqli_query($connection, "DELETE FROM task WHERE task_id='$task_id' ");
      header("Location: index.php");
    }

?>

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>TODOLIST</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <h1 class="text-center" style="font-family: monospace">TODOLIST</h1>
        </div>
      </div>

      <div class="row">
        <div class="col-md-6">
          <div class="card shadow-lg border-0">
            <div class="card-body">
              <h3 style="font-family: monospace">Add Task</h3>
              <form method="post">
                <div class="form-group">
                  <input
                    type="text"
                    name="task_name"
                    class="form-control"
                    placeholder="Input Task"
                  />
                </div>
                <div class="form-group">
                  <button
                    type="submit"
                    name="add_post"
                    class="btn btn-outline-primary"
                  >
                    Add
                  </button>
                </div>
              </form>

              <h3 style="font-family: monospace">Waiting Task List</h3>
              <ul class="list-group">
                <?php 
                $query = mysqli_query($connection, "SELECT * FROM task WHERE task_status='pending' ");
                while($row = mysqli_fetch_array($query)){
                    $task_name = $row['task_name'];
                ?>
                <li class="list-group-item">
                  <?php echo $task_name; ?>
                  <div class="float-right">
                    <a
                      href="index.php?edit=<?php echo $row['task_id']; ?>"
                      class="btn btn-info"
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        fill="currentColor"
                        class="bi bi-check2-all"
                        viewBox="0 0 16 16"
                      >
                        <path
                          d="M12.354 4.354a.5.5 0 0 0-.708-.708L5 10.293 1.854 7.146a.5.5 0 1 0-.708.708l3.5 3.5a.5.5 0 0 0 .708 0l7-7zm-4.208 7-.896-.897.707-.707.543.543 6.646-6.647a.5.5 0 0 1 .708.708l-7 7a.5.5 0 0 1-.708 0z"
                        />
                        <path
                          d="m5.354 7.146.896.897-.707.707-.897-.896a.5.5 0 1 1 .708-.708z"
                        />
                      </svg>
                    </a>

                    <a
                      href="index.php?delete=<?php echo $row['task_id']; ?>"
                      class="btn btn-danger"
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        fill="currentColor"
                        class="bi bi-trash"
                        viewBox="0 0 16 16"
                      >
                        <path
                          d="M5.5 5.5A.5.5 0 0 1 6 6v6a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5zm2.5 0a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5zm3 .5a.5.5 0 0 0-1 0v6a.5.5 0 0 0 1 0V6z"
                        />
                        <path
                          fill-rule="evenodd"
                          d="M14.5 3a1 1 0 0 1-1 1H13v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V4h-.5a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1H6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1h3.5a1 1 0 0 1 1 1v1zM4.118 4 4 4.059V13a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V4.059L11.882 4H4.118zM2.5 3V2h11v1h-11z"
                        />
                      </svg>
                    </a>
                  </div>
                </li>
                <?php } ?>
              </ul>
            </div>
          </div>
        </div>

        <div class="col-md-6">
          <div class="card shadow-lg border-0">
            <div class="card-body">
              <h3 style="font-family: monospace">Completed Task List</h3>
              <ul class="list-group">
                <?php 
                    $query = mysqli_query($connection, "SELECT * FROM task WHERE task_status='DONE' ");
                    while($row = mysqli_fetch_array($query)){
                ?>
                <li class="list-group-item">
                  <?php echo $row['task_name']; ?>

                  <div class="float-right">
                    <span class="badge bg-primary"
                      ><?php echo $row['task_status']; ?></span
                    >
                  </div>
                </li>
                <?php } ?>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
