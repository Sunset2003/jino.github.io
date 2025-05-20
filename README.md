<div class="blog-stats">
  <div class="stat-card">
    <i class="fas fa-tag"></i>
    <h3>12 标签</h3>
    <a href="/tags" class="gradient-btn">查看所有</a>
  </div>

  <div class="stat-card">
    <i class="fas fa-comments"></i>
    <h3>24 评论</h3>
    <div class="comment-preview">最新：感谢分享！</div>
  </div>

  <div class="stat-card">
    <i class="fas fa-feather"></i>
    <h3>56 文章</h3>
    <div class="update-time">最近更新：今天</div>
  </div>
</div>

<style>
.blog-stats {
  display: grid;
  gap: 2rem;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
}

.stat-card {
  background: var(--card-bg);
  padding: 2rem;
  border-radius: 12px;
  box-shadow: var(--card-shadow);
  transition: transform 0.3s ease;
  
  &:hover {
    transform: translateY(-5px);
  }
  
  i {
    font-size: 2.5rem;
    color: var(--primary);
  }
}

.gradient-btn {
  background: linear-gradient(135deg, var(--primary), var(--secondary));
  color: white;
  padding: 8px 20px;
  border-radius: 25px;
  display: inline-block;
  margin-top: 1rem;
}
</style>
