<template>
    <div class="user-list-container mx-auto" id="userList">
        <div class="clearfix">
            <button class="btn btn-sm btn-success float-right mb-3">Create new user</button>
        </div>
        <div class="list-group">
            <div class="list-group-item txt-left" v-for="user in users" :key="user.id">
                {{ user.name }}
                    <div class="btn-group float-right">
                        <button class="btn btn-sm btn-danger">
                            Delete User
                        </button>
                        <button class="btn btn-sm btn-primary">
                            Edit User
                        </button>
                    </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'UserList',
  props: {
    msg: String
  },
    data: () => {
        return {
            users: [
                {
                    name: 'User1',
                    id: Math.random(),
                    isAdmin: false
                },
                {
                    name: 'User2',
                    id: Math.random(),
                    isAdmin: false
                }
            ]
        }
    }
}
</script>
<style>
.user-list-container {
  width: 400px;
}
</style>