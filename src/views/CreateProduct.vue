<template>
  <div class="admin">
    <div class="admin-table">
      <div class="d-flex mb-70">
        <button
          type="button"
          class="btn btn-primary ms-auto"
          data-bs-toggle="modal"
          data-bs-target="#exampleModal"
        >
          Yangilik kiritish
        </button>
      </div>

      <!-- Modal -->
      <div
        class="modal fade"
        id="exampleModal"
        tabindex="-1"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog modal-dialog-scrollable">
          <div class="modal-content">
            <form class="p-3">
              <div class="mb-3">
                <label for="exampleInputEmail1" class="form-label"
                  >Mahsulot nomi</label
                >
                <input
                  type="text"
                  class="form-control"
                  v-model="title"
                  id="exampleInputEmail1"
                  aria-describedby="emailHelp"
                  placeholder="Iphone 13 Pro Max"
                />
              </div>
              <div class="mb-3">
                <label for="exampleInputPassword1" class="form-label"
                  >Mahsulot haqida</label
                >
                <textarea
                  v-model="description"
                  class="form-control"
                  id="exampleFormControlTextarea1"
                  rows="3"
                ></textarea>
              </div>
              <div class="mb-3">
                <label for="exampleInputEmail1" class="form-label"
                  >Mahsulot narxi sumda</label
                >
                <input
                  type="number"
                  class="form-control"
                  v-model="title"
                  id="exampleInputEmail1"
                  aria-describedby="emailHelp"
                  placeholder="300 000 sum"
                />
              </div>
              <div class="mb-3">
                <label htmlFor="fileInput" className="text-start mt-3">
                  Rasmni tanlang:
                  <input
                    type="file"
                    id="fileInput"
                    className="form-control text-start "
                    accept=".jpg, .jpeg, .png"
                    required
                  />
                </label>
              </div>
              <button class="btn" data-bs-dismiss="modal">Close</button>
              <button
                type="submit"
                class="btn btn-primary"
                data-bs-dismiss="modal"
              >
                Qo'shish
              </button>
            </form>
          </div>
        </div>
      </div>
      <div class="scroll-x">
        <table class="table">
          <thead>
            <tr>
              <th scope="col">№</th>
              <th scope="col" class="ps-5 text-nowrap">Mahsulot rasmi</th>
              <th scope="col">Mahsulot</th>
              <th scope="col">Mahsulot haqida</th>
              <th scope="col" class="text-nowrap">Mahsulot narxi</th>
              <th scope="col"></th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row">1</th>
              <td class="table-img">
                <img
                  src="https://cdn.shopclues.com/images1/thumbnails/116250/320/320/153050056-116250401-1649837829.jpg"
                  alt=""
                />
              </td>
              <td>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</td>
              <td>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quo
                dolores ab neque ad voluptatibus minima eius, qui fugiat
                explicabo quas consectetur maiores inventore adipisci,
                asperiores ex recusandae quod. Eligendi, dignissimos.
              </td>
              <td>300 000 sum</td>
              <td class="d-flex gap-3">
                <button class="admin-btn">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="blue"
                    class="bi bi-pencil-fill"
                    viewBox="0 0 16 16"
                  >
                    <path
                      d="M12.854.146a.5.5 0 0 0-.707 0L10.5 1.793 14.207 5.5l1.647-1.646a.5.5 0 0 0 0-.708l-3-3zm.646 6.061L9.793 2.5 3.293 9H3.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.207l6.5-6.5zm-7.468 7.468A.5.5 0 0 1 6 13.5V13h-.5a.5.5 0 0 1-.5-.5V12h-.5a.5.5 0 0 1-.5-.5V11h-.5a.5.5 0 0 1-.5-.5V10h-.5a.499.499 0 0 1-.175-.032l-.179.178a.5.5 0 0 0-.11.168l-2 5a.5.5 0 0 0 .65.65l5-2a.5.5 0 0 0 .168-.11l.178-.178z"
                    />
                  </svg>
                  <span class="text-blue">Edit</span>
                </button>
                <button class="admin-btn" @click="gameId(item.id)">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="red"
                    class="bi bi-trash3"
                    viewBox="0 0 16 16"
                  >
                    <path
                      d="M6.5 1h3a.5.5 0 0 1 .5.5v1H6v-1a.5.5 0 0 1 .5-.5ZM11 2.5v-1A1.5 1.5 0 0 0 9.5 0h-3A1.5 1.5 0 0 0 5 1.5v1H2.506a.58.58 0 0 0-.01 0H1.5a.5.5 0 0 0 0 1h.538l.853 10.66A2 2 0 0 0 4.885 16h6.23a2 2 0 0 0 1.994-1.84l.853-10.66h.538a.5.5 0 0 0 0-1h-.995a.59.59 0 0 0-.01 0H11Zm1.958 1-.846 10.58a1 1 0 0 1-.997.92h-6.23a1 1 0 0 1-.997-.92L3.042 3.5h9.916Zm-7.487 1a.5.5 0 0 1 .528.47l.5 8.5a.5.5 0 0 1-.998.06L5 5.03a.5.5 0 0 1 .47-.53Zm5.058 0a.5.5 0 0 1 .47.53l-.5 8.5a.5.5 0 1 1-.998-.06l.5-8.5a.5.5 0 0 1 .528-.47ZM8 4.5a.5.5 0 0 1 .5.5v8.5a.5.5 0 0 1-1 0V5a.5.5 0 0 1 .5-.5Z"
                    />
                  </svg>
                  <span class="text-red"> Delete</span>
                </button>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
  <script>
export default {};
</script>
  
  <style lang="scss">
.modal-dialog {
  padding: 30px;
}
.text- {
  &red {
    color: red;
  }
  &blue {
    color: blue;
  }
}

.table {
  overflow: scroll;
  tr {
    td {
      &:nth-child(3) {
        max-width: 200px;
      }
    }
    td,
    th {
      &:first-child {
        width: 20px;
      }
    }
  }
  &-img {
    width: 150px;
    height: 100px;
    border-radius: 8px;
    overflow: hidden;
    &.small {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      overflow: hidden;
      img {
        border-radius: 50%;
        overflow: hidden;
        object-fit: cover;
        background-size: cover;
      }
    }
    img {
      width: 100%;
      height: 100%;
      background-repeat: no-repeat;
      object-fit: contain;
    }
  }
}
.admin {
  display: flex;
  flex-wrap: wrap;
  margin-top: 80px;
  &-left {
    display: none;
    width: 0px;
    min-height: 0px;
    transition: 0.5s;
    &.dn {
      width: 300px;
      min-height: 60vh;
      display: flex;
      transition: 0.5s;
    }
  }
  &-btn {
    background: #a5a2a2;
    padding: 8px 16px;
    display: flex;
    justify-content: center;
    align-items: center;
    white-space: nowrap;
    border: none;
    width: 100px;
    border-radius: 8px;
    margin-top: 30px;
    &:hover {
      transform: scale(1.05);
    }
    svg {
      margin-right: 10px;
    }
  }
  &-table {
    width: 100%;
    padding: 40px;
    flex-direction: column;
    justify-content: flex-end;
    align-items: flex-end;
    overflow-x: scroll;
    padding-top: 0;
    &.big {
      width: calc(100% - 300px);
      overflow-y: scroll;
    }
  }
  .flex-shrink-0 {
    margin-top: -40px;
    padding-top: 100px;
  }
}
.nav {
  li {
    margin-top: 30px;
    list-style-type: none;
    font-size: 23px;
    &:hover {
      background-color: rgb(76, 108, 250);
      border-radius: 8px;
      a {
        color: #fff;
      }
    }
  }
}

@media (max-width: 900px) {
  .table {
    width: 900px;
  }
  .admin-left {
    display: none;
  }
  .admin-table {
    width: 100%;
  }
}
</style>